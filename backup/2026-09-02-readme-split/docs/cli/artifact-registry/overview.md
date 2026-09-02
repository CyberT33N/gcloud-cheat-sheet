# Artifact Repository



# Repositories


## List
```shell
gcloud artifacts repositories list --project=test-go-builder-authority --location=europe-west3 --format="table(name,format,mode,description)"
```


## Describe
```shell
gcloud artifacts repositories describe go-builder-staging-images --project=test-go-builder-authority --location=europe-west3 --format="yaml(name,format,dockerConfig,labels,vulnerabilityScanningConfig)"
```


## Create
```shell
gcloud artifacts repositories create go-builder-approved-images --project=test-go-builder-authority --location=europe-west3 --repository-format=docker --immutable-tags --disable-vulnerability-scanning --description="Immutable approved Go builder images" --labels="authority=go_builder,lane=approved,subject=builder" --quiet
```
