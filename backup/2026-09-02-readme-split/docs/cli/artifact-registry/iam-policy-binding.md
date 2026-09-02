# iam policy binding

# Add

```shell
gcloud artifacts repositories add-iam-policy-binding go-builder-staging-images --project=test-go-builder-authority --location=europe-west3 --member="serviceAccount:gba-builder-staging-deployer@test-go-builder-authority.iam.gserviceaccount.com" --role="roles/artifactregistry.writer" --quiet
```


# get

```shell
gcloud artifacts repositories get-iam-policy go-builder-staging-images --project=test-go-builder-authority --location=europe-west3 --format="yaml(bindings)"
```
