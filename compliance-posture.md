## Catalog
Test Catalog
## Component: Kubernetes
#### Result of control: cm-8.3_smt.a

Rule ID: advanced-restrict-image-registries
  - No subjects found


Rule ID: allowed-base-images
<details><summary>Details</summary>

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: fail
    - Reason:
      ```
      validation failure: This container image&#39;s base is not in the approved list or is not specified. Only pre-approved base images may be used. Please contact the platform team for assistance.
      ```
</details>


Rule ID: allowed-image-repos
  - No subjects found

---
#### Result of control: ac-3

Rule ID: allowed-label-changes
  - No subjects found

---
#### Result of control: ac-6

Rule ID: allowed-label-changes
  - No subjects found

---
#### Result of control: ac-4

Rule ID: allowed-podpriorities
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority&#39; passed.
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-cronjob-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-cronjob-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.jobTemplate.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.jobTemplate.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```
</details>


Rule ID: podsecurity-subrule-baseline
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;xtables-lock&#34;, &#34;lib-modules&#34;})
({Allowed:false ForbiddenReason:privileged ForbiddenDetail:container &#34;kube-proxy&#34; must not set securityContext.privileged=true})

      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:non-default capabilities ForbiddenDetail:container &#34;kindnet-cni&#34; must not include &#34;NET_ADMIN&#34;, &#34;NET_RAW&#34; in securityContext.capabilities.add})
({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;cni-cfg&#34;, &#34;xtables-lock&#34;, &#34;lib-modules&#34;})

      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;etcd-certs&#34;, &#34;etcd-data&#34;})

      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;xtables-lock&#34;, &#34;lib-modules&#34;})
({Allowed:false ForbiddenReason:privileged ForbiddenDetail:container &#34;kube-proxy&#34; must not set securityContext.privileged=true})

      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:non-default capabilities ForbiddenDetail:container &#34;kindnet-cni&#34; must not include &#34;NET_ADMIN&#34;, &#34;NET_RAW&#34; in securityContext.capabilities.add})
({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;cni-cfg&#34;, &#34;xtables-lock&#34;, &#34;lib-modules&#34;})

      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volume &#34;kubeconfig&#34;})

      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;ca-certs&#34;, &#34;etc-ca-certificates&#34;, &#34;flexvolume-dir&#34;, &#34;k8s-certs&#34;, &#34;kubeconfig&#34;, &#34;usr-local-share-ca-certificates&#34;, &#34;usr-share-ca-certificates&#34;})

      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;ca-certs&#34;, &#34;etc-ca-certificates&#34;, &#34;k8s-certs&#34;, &#34;usr-local-share-ca-certificates&#34;, &#34;usr-share-ca-certificates&#34;})

      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-cronjob-baseline&#39; passed.
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-cronjob-baseline&#39; passed.
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```
</details>


Rule ID: block-ephemeral-containers
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-cronjob-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-cronjob-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```
</details>


Rule ID: block-images-with-volumes
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: fail
    - Reason:
      ```
      validation failure: Images containing built-in volumes are prohibited.
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: fail
    - Reason:
      ```
      validation failure: Images containing built-in volumes are prohibited.
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      rule passed
      ```
</details>


Rule ID: deny-exec-by-namespace-label
  - No subjects found


Rule ID: deny-exec-by-namespace-name
  - No subjects found


Rule ID: deny-exec-by-pod-and-container
  - No subjects found


Rule ID: deny-exec-by-pod-label
  - No subjects found


Rule ID: deny-exec-by-pod-name
  - No subjects found


Rule ID: block-updates-deletes
  - No subjects found


Rule ID: block-velero-restore
  - No subjects found

---
#### Result of control: ac-6

Rule ID: allowed-podpriorities
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority&#39; passed.
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-cronjob-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-cronjob-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.jobTemplate.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: error
    - Reason:
      ```
      failed to check deny preconditions: failed to substitute variables in condition key: failed to resolve request.object.spec.jobTemplate.spec.template.spec.priorityClassName at path : JMESPath query failed: Unknown key &#34;priorityClassName&#34; in path
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-validate-pod-priority-pods&#39; passed.
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      validation rule &#39;validate-pod-priority-pods&#39; passed.
      ```
</details>


Rule ID: podsecurity-subrule-baseline
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;xtables-lock&#34;, &#34;lib-modules&#34;})
({Allowed:false ForbiddenReason:privileged ForbiddenDetail:container &#34;kube-proxy&#34; must not set securityContext.privileged=true})

      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:non-default capabilities ForbiddenDetail:container &#34;kindnet-cni&#34; must not include &#34;NET_ADMIN&#34;, &#34;NET_RAW&#34; in securityContext.capabilities.add})
({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;cni-cfg&#34;, &#34;xtables-lock&#34;, &#34;lib-modules&#34;})

      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;etcd-certs&#34;, &#34;etcd-data&#34;})

      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;xtables-lock&#34;, &#34;lib-modules&#34;})
({Allowed:false ForbiddenReason:privileged ForbiddenDetail:container &#34;kube-proxy&#34; must not set securityContext.privileged=true})

      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:non-default capabilities ForbiddenDetail:container &#34;kindnet-cni&#34; must not include &#34;NET_ADMIN&#34;, &#34;NET_RAW&#34; in securityContext.capabilities.add})
({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;cni-cfg&#34;, &#34;xtables-lock&#34;, &#34;lib-modules&#34;})

      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volume &#34;kubeconfig&#34;})

      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;ca-certs&#34;, &#34;etc-ca-certificates&#34;, &#34;flexvolume-dir&#34;, &#34;k8s-certs&#34;, &#34;kubeconfig&#34;, &#34;usr-local-share-ca-certificates&#34;, &#34;usr-share-ca-certificates&#34;})

      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;ca-certs&#34;, &#34;etc-ca-certificates&#34;, &#34;k8s-certs&#34;, &#34;usr-local-share-ca-certificates&#34;, &#34;usr-share-ca-certificates&#34;})

      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-cronjob-baseline&#39; passed.
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-cronjob-baseline&#39; passed.
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```
</details>


Rule ID: block-cluster-admin-from-ns
  - No subjects found


Rule ID: block-ephemeral-containers
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-cronjob-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-cronjob-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      validation rule &#39;autogen-block-ephemeral-containers&#39; passed.
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      validation rule &#39;block-ephemeral-containers&#39; passed.
      ```
</details>


Rule ID: deny-exec-by-namespace-label
  - No subjects found


Rule ID: deny-exec-by-namespace-name
  - No subjects found


Rule ID: deny-exec-by-pod-and-container
  - No subjects found


Rule ID: deny-exec-by-pod-label
  - No subjects found


Rule ID: deny-exec-by-pod-name
  - No subjects found


Rule ID: block-updates-deletes
  - No subjects found


Rule ID: block-velero-restore
  - No subjects found

---
#### Result of control: ac-3

Rule ID: podsecurity-subrule-baseline
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;xtables-lock&#34;, &#34;lib-modules&#34;})
({Allowed:false ForbiddenReason:privileged ForbiddenDetail:container &#34;kube-proxy&#34; must not set securityContext.privileged=true})

      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:non-default capabilities ForbiddenDetail:container &#34;kindnet-cni&#34; must not include &#34;NET_ADMIN&#34;, &#34;NET_RAW&#34; in securityContext.capabilities.add})
({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;cni-cfg&#34;, &#34;xtables-lock&#34;, &#34;lib-modules&#34;})

      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;etcd-certs&#34;, &#34;etcd-data&#34;})

      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;xtables-lock&#34;, &#34;lib-modules&#34;})
({Allowed:false ForbiddenReason:privileged ForbiddenDetail:container &#34;kube-proxy&#34; must not set securityContext.privileged=true})

      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:non-default capabilities ForbiddenDetail:container &#34;kindnet-cni&#34; must not include &#34;NET_ADMIN&#34;, &#34;NET_RAW&#34; in securityContext.capabilities.add})
({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;cni-cfg&#34;, &#34;xtables-lock&#34;, &#34;lib-modules&#34;})

      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volume &#34;kubeconfig&#34;})

      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;ca-certs&#34;, &#34;etc-ca-certificates&#34;, &#34;flexvolume-dir&#34;, &#34;k8s-certs&#34;, &#34;kubeconfig&#34;, &#34;usr-local-share-ca-certificates&#34;, &#34;usr-share-ca-certificates&#34;})

      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: fail
    - Reason:
      ```
      Validation rule &#39;baseline&#39; failed. It violates PodSecurity &#34;baseline:latest&#34;: ({Allowed:false ForbiddenReason:host namespaces ForbiddenDetail:hostNetwork=true})
({Allowed:false ForbiddenReason:hostPath volumes ForbiddenDetail:volumes &#34;ca-certs&#34;, &#34;etc-ca-certificates&#34;, &#34;k8s-certs&#34;, &#34;usr-local-share-ca-certificates&#34;, &#34;usr-share-ca-certificates&#34;})

      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-cronjob-baseline&#39; passed.
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-cronjob-baseline&#39; passed.
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;autogen-baseline&#39; passed.
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      Validation rule &#39;baseline&#39; passed.
      ```
</details>


Rule ID: block-cluster-admin-from-ns
  - No subjects found


Rule ID: deny-exec-by-namespace-label
  - No subjects found


Rule ID: deny-exec-by-namespace-name
  - No subjects found


Rule ID: deny-exec-by-pod-and-container
  - No subjects found


Rule ID: deny-exec-by-pod-label
  - No subjects found


Rule ID: deny-exec-by-pod-name
  - No subjects found

---
#### Result of control: ac-2_smt.d

Rule ID: block-cluster-admin-from-ns
  - No subjects found

---
#### Result of control: ac-5_smt.c

Rule ID: block-cluster-admin-from-ns
  - No subjects found

---
#### Result of control: sc-5

Rule ID: block-large-images
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      rule passed
      ```
</details>

---
#### Result of control: cm-8.3_smt.a

Rule ID: block-stale-images
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      rule passed
      ```
</details>


Rule ID: check-deprecated-apis
  - No subjects found

---
#### Result of control: si-2.2

Rule ID: block-stale-images
<details><summary>Details</summary>

  - Subject UUID: 23d25075-da9c-41aa-a73e-e317770c377d
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: argocd, Name: argocd-server
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 247d76c2-b43c-49ec-a501-efdbb9752b67
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 25313824-108c-43e4-a6d7-d404702d6e66
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 2d022b83-c9ab-4b49-be03-95b60dc4ec0f
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-dex-server-bb76f899c
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 391726d5-ac35-41b7-bd4f-67ef345b2677
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-redis-b5d6bf5f5
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 71ef51a8-67ca-4e57-8d77-24f4206ac841
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 81797cb9-31c0-4872-a958-b167836b6cff
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-server-5985b6cf6f
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: ca513c3b-2054-4db1-8df3-23ec18b5680d
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: argocd, Name: argocd-repo-server-56998dcf9c
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: cf61f7f0-cd9a-44f6-ab07-ddc83a31c6de
    - Title: ApiVersion: apps/v1, Kind: StatefulSet, Namespace: argocd, Name: argocd-application-controller
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 0b1adf1c-f6e2-46af-889e-39255e669655
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-application-controller-0
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 3c7a83c8-abc9-4041-aafd-16da906f9efc
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-server-5985b6cf6f-5cbcw
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 4db11e78-ef68-4003-bef7-c24d35a48951
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-repo-server-7ccbc8cb48-f4nxv
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 66c9292a-091b-4325-ac28-44080e305f8c
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-notifications-controller-5557f7bb5b-knkhk
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 89fc793e-e686-4653-a838-3fe4ac37b1bf
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-redis-b5d6bf5f5-hx2bh
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: e7a4e6fe-7380-4c59-86ad-6a5f1a924e39
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-dex-server-bb76f899c-crpgz
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: fc29d94c-115f-4351-94eb-4839d3e30a78
    - Title: ApiVersion: v1, Kind: Pod, Namespace: argocd, Name: argocd-applicationset-controller-787bfd9669-64886
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 3850baa8-0b50-4cee-b3ae-e2ca857bd2f1
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kube-proxy
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 8c1de00f-7c26-408c-89ae-40c4af347467
    - Title: ApiVersion: apps/v1, Kind: DaemonSet, Namespace: kube-system, Name: kindnet
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: fe901839-d4d0-4614-a83d-f1747cba5905
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kube-system, Name: coredns-5d78c9869d
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 18b1d403-dde5-4b77-97e1-af25f8dd5f97
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: etcd-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 1c99caf6-f89a-493e-86cc-654a7987d2c1
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-proxy-wsl9b
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 4861beaf-4981-4e21-9b62-a65310b3d6af
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-pwc6s
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 67b1d4ca-2d17-4c02-983b-cca88998688a
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kindnet-9gpsc
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 96b4a7a8-69e7-4487-a5fb-55e6cef6d81f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-scheduler-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: a1ff9879-6c0c-4199-8b6a-e8002bdb5468
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: coredns-5d78c9869d-v4bzh
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: c59c011a-3a47-47bc-8abf-9bab2b228b4f
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-controller-manager-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: d945abb0-0b11-4e32-b4fa-2dabcc325be0
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kube-system, Name: kube-apiserver-kind-control-plane
    - Result: fail
    - Reason:
      ```
      validation failure: Images built more than 6 months ago are prohibited.
      ```

  - Subject UUID: 19fe628b-828c-4ac6-b0f8-c74112466334
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9777357f-3598-4ba0-9142-f554601b7544
    - Title: ApiVersion: apps/v1, Kind: Deployment, Namespace: kyverno, Name: kyverno-cleanup-controller
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9a97ba34-8310-4a60-a5a6-112f17b2bfe5
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 9bf6595a-21af-4d05-b054-7db0e37638e8
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-background-controller-74599787cf
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: f2185ef7-aa43-48cb-abd1-e21fbfb79b0a
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 1f7dd3fe-6995-4205-a34e-dabbbe2081f9
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 54aecd37-31c1-490f-a963-0079e9e1bc37
    - Title: ApiVersion: batch/v1, Kind: CronJob, Namespace: kyverno, Name: kyverno-cleanup-admission-reports
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 16e915d2-816c-4560-811b-3b68d32f9669
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-cluster-admission-reports-28293520-hml9q
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 372c612a-5548-4925-9916-ce8c5b070eb6
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-admission-reports-28293520-4ck6h
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 47e9644c-4ec5-4655-a157-be4330c7cad5
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-background-controller-74599787cf-69cc2
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 956e9d43-c37c-47fe-8d12-46ffa00cf081
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-admission-controller-7cd788c8dd-gmhzv
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: a1035b1f-4555-467a-8c24-f319a5f77387
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-cleanup-controller-ddf458755-zjdhx
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: e5f132fc-c45f-42e8-8c64-04d1a9b10a94
    - Title: ApiVersion: v1, Kind: Pod, Namespace: kyverno, Name: kyverno-reports-controller-7f94855747-t2pbd
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: bfe41dbc-02cc-4378-bbf8-532a5bc570b6
    - Title: ApiVersion: apps/v1, Kind: ReplicaSet, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b
    - Result: pass
    - Reason:
      ```
      rule passed
      ```

  - Subject UUID: 851841df-c869-4fce-b745-4d2c65f81aa4
    - Title: ApiVersion: v1, Kind: Pod, Namespace: local-path-storage, Name: local-path-provisioner-6bc4bddd6b-4tbp5
    - Result: pass
    - Reason:
      ```
      rule passed
      ```
</details>


Rule ID: check-deprecated-apis
  - No subjects found

---
#### Result of control: ia-5_smt.g

Rule ID: cert-manager-limit-duration
  - No subjects found

---
#### Result of control: cp-2

Rule ID: k10-3-2-1-backup-policy
  - No subjects found

---
#### Result of control: cp-9

Rule ID: k10-3-2-1-backup-policy
  - No subjects found

---
#### Result of control: cp-10

Rule ID: k10-policy-hourly-rpo
  - No subjects found

---
