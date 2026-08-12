# Artifact Repository

# API

## Enable
```shell
gcloud services enable artifactregistry.googleapis.com --project=test-go-builder-authority --quiet
```




---

# Repositories


## List
```shell
gcloud artifacts repositories list --project=test-go-builder-authority --location=europe-west3 --format="table(name,format,mode,description)"
```





## Create
```shell
gcloud artifacts repositories create go-builder-approved-images --project=test-go-builder-authority --location=europe-west3 --repository-format=docker --immutable-tags --disable-vulnerability-scanning --description="Immutable approved Go builder images" --labels="authority=go_builder,lane=approved,subject=builder" --quiet
```
