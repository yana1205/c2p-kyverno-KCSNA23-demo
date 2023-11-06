## C2P Continuous Compliance Pipeline (Demo at Kuberentes Contributor Summit North America 2023)

## Outline
1. Setup the pipeline repository
1. Setup KinD cluster with Kyverno and ArgoCD installed
1. Demo (upload a csv describing Compliance controls)

### 1. Setup pipeline repository
1. Fork this repository
1. Go to `Actions` tab in your forked repository and enable workflows
1. Create a new branch (`results`) for storing PVP assessment results
1. Create access token (will be used later)
    1. Go to [Settings/Developer Settings Fine-grained personal access tokens](https://github.com/settings/tokens?type=beta)
    1. Generate New Token
        1. Select Repository Access with `Only select repositories` and select your forked repository
        1. Select Permissions with `Contents` and `Pull requests` with `Read and Write` access
        1. Go `Generate Token`

### 2. Setup KinD cluster with Kyverno and ArgoCD installed
1. Create a cluster
    ```
    kind create cluster --wait 5m
    ```
1. Install Kyverno (https://kyverno.io)
    ```
    kubectl create -f https://github.com/kyverno/kyverno/releases/download/v1.10.0/install.yaml
    ```
1. Install ArgoCD (https://argo-cd.readthedocs.io/en/stable/getting_started/)
    ```
    ./scripts/install-argocd.sh --interval 60s
    ```
1. Setup ArgoCD to sync the pipeline repository
    ```
    ./scripts/setup-argocd.sh --user <your github username> --token <created github personal access token> --org <your github organization> --repo <repository name>
    ```
    For example of https://github.com/yana1205/c2p-for-kyverno1008-config
    ```
    ./scripts/setup-argocd.sh --user yana1205 --token $PAT --org yana1205 --repo c2p-for-kyverno1008-config
    ```
1. Setup cronjob to push Kyverno audit results (PolicyReports, ClusterPolicyReports, Policy, and ClusterPolicy) to the pipeline repo
   1. Create c2p namespace
        ```
        kubectl create ns c2p
        ```
   1. Create the github access credentials (github username, organization, repository, and personal access token) in secret
        ```
        kubectl -n c2p create secret generic --save-config kyverno-policy-report-secret --from-literal=token=<github personal access token> --from-literal=user=<your github username> --from-literal=repo=<repository name> --from-literal=org=<your github organization>
        ```
        For example of https://github.com/yana1205/c2p-for-kyverno1008-config
        ```
        kubectl -n c2p create secret generic --save-config kyverno-policy-report-secret --from-literal=token=$PAT --from-literal=user=yana1205 --from-literal=repo=c2p-for-kyverno1008-config --from-literal=org=yana1205
        ```
   1. Deploy c2p status upsync cronjob
        ```
        kubectl apply -f ./scripts/upsync
        ```

### 3. Demo
The goal is to wire the process for Continuous Compliance of Compliance Controls documentation authoring, Policy validation/enforcement, and Compliance Posture.

1. Go to `https://github.com/<your org>/<your pipeline repo>/tree/main/data` and upload a csv describing Compliance controls (./scripts/samples/component-definition-kube.csv) by `Add file`
    1. GitHub action to generate OSCAL Component Definition starts and creates a PR (If not triggered due to some reason, try to run `Generate Component Definition` workflow manually)
1. Merge the PR
    1. GitHub action to generate Kyverno Policies starts and creates a PR (the generated policies are located in ./kyverno-policies directory)
1. Merge the PR
    1. ArgoCD syncs the generated Kyverno Policies in few minutes later (watch `kubectl get pol,cpol,polr,cpolr -A`)
    1. The upsync cronjob will upload the policy reports to `results` branch (wait for the latest policyreports to be uploaded to `https://github.com/<your github org>/<your repo name>/tree/results/policy-reports`)
1. Run `Result to OSCAL` GitHub action
    1. It generates OSCAL Assessment Results and creates a PR
1. Merge the PR
    1. GitHub action to generate Compliance Posture in markdown format and creates a PR
1. Done. You can review the Compliance Posture corresponding to the Compliance Controls that we defined in csv. The goal is achieved.

### 4. Cleanup
1. Go to GitHub Actions and run `Clear all artifacts`
    1. GitHub action to delete all generated artifacts starts and creates a PR
1. Merge the PR
    1. Make sure that all policies are removed (the following command displays nothing few minutes later)
        ```
        kubectl get pol,cpol,polr,cpolr -A
        ```
1. Delete c2p status upsync cronjob
    ```
    kubectl delete -f ./scripts/upsync
    ```
1. Now you can retry `3. Demo`.

### Cleanup all
1. After going through `4. Cleanup`, delete KinD cluster
    ```
    kind delete cluster
    ```