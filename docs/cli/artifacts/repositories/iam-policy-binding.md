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

`roles/artifactregistry.reader` carries `artifactregistry.repositories.downloadArtifacts` (proven via `gcloud iam roles describe`). Without this binding the job creation reports `ContainerPermissionDenied`; the job resource is still created, and its `Ready` condition recovers after the grant plus a re-validation (see the run jobs [update](../run/jobs/update/overview.md) note).
