# Add iam policy binding

```shell
gcloud artifacts repositories add-iam-policy-binding go-builder-staging-images --project=test-go-builder-authority --location=europe-west3 --member="serviceAccount:gba-builder-staging-deployer@test-go-builder-authority.iam.gserviceaccount.com" --role="roles/artifactregistry.writer" --quiet
```
