# IAM Policy Binding

[INTENT: REFERENCE]

## Add

```shell
gcloud artifacts repositories add-iam-policy-binding go-builder-staging-images --project=test-go-builder-authority --location=europe-west3 --member="serviceAccount:gba-builder-staging-deployer@test-go-builder-authority.iam.gserviceaccount.com" --role="roles/artifactregistry.writer" --quiet
```

## Get

```shell
gcloud artifacts repositories get-iam-policy go-builder-staging-images --project=test-go-builder-authority --location=europe-west3 --format="yaml(bindings)"
```

## Get (JSON form for scriptable read-back)

```shell
gcloud artifacts repositories get-iam-policy release-controller-images --project=test-software-dep-control --location=europe-west3 --format=json
```

## Cross-project Cloud Run image pull (service agent member)

When a Cloud Run job or service in project A runs an image from a repository in project B, the pull is performed by the Cloud Run Service Agent of project A, not by the workload identity. Grant the agent read access on the source repository:

```shell
gcloud artifacts repositories add-iam-policy-binding release-controller-images --project=test-software-dep-control --location=europe-west3 --member="serviceAccount:service-xxxxxxxxxxxx@serverless-robot-prod.iam.gserviceaccount.com" --role="roles/artifactregistry.reader"
```

[`roles/artifactregistry.reader`](../../../iam/roles/predefined/artifactregistry/reader/overview.md) carries `artifactregistry.repositories.downloadArtifacts` (proven via `gcloud iam roles describe`). Without this binding the job creation reports `ContainerPermissionDenied`; the job resource is still created, and its `Ready` condition recovers after the grant plus a re-validation (see the run jobs [update](../run/jobs/update/overview.md) note).

## Remove

```shell
gcloud artifacts repositories remove-iam-policy-binding go-dependencies-evidence --project=test-software-dep-evidence --location=europe-west3 --member="user:<EMAIL>" --role="roles/artifactregistry.writer"
```

Remove exactly the member form previously read from the live policy and prove the removal by an independent `get-iam-policy` read-back. Full form and troubleshooting: [remove-iam-policy-binding](remove-iam-policy-binding/overview.md).

## Precondition for policy management (proven)

Both `add-iam-policy-binding` and `remove-iam-policy-binding` read and write the repository IAM policy, so the caller must hold `artifactregistry.repositories.getIamPolicy` and `artifactregistry.repositories.setIamPolicy` on the repository. Data-plane roles do not carry them — [`roles/artifactregistry.writer`](../../../iam/roles/predefined/artifactregistry/writer/overview.md) provably contains neither (role-content inspection), and a direct call fails closed with `PERMISSION_DENIED: Permission 'artifactregistry.repositories.getIamPolicy' denied`. The minimal predefined role carrying them is [`roles/artifactregistry.admin`](../../../iam/roles/predefined/artifactregistry/admin/overview.md); the proven pattern is the bounded management wrapper: grant admin, set or remove the data-plane binding, remove admin, and prove the hardened end state by read-back.
