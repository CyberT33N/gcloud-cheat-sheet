# Services

## List
```shell
gcloud run services list --project=git-governance-release-broker --region=europe-west3 2>&1; gcloud artifacts repositories list --project=git-governance-release-broker --location=europe-west3 2>&1
```

## Describe
```shell
gcloud run services describe git-governance-release-broker --project=git-governance-release-broker --region=europe-west3 --format="yaml(spec.template.spec.containers[0].env)" 2>&1
```


---

## Enable

### IAM
```shell
gcloud services enable iam.googleapis.com --project=t33n-go-builder-authority --quiet
```

### Secret Store
```shell
gcloud services enable sts.googleapis.com --project=t33n-go-builder-authority --quiet
```

### Artifact Registry

```shell
gcloud services enable artifactregistry.googleapis.com --project=test-go-builder-authority --quiet
```
