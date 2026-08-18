
# Repositories


## Describe
```shell
gcloud artifacts repositories describe go-dependencies-intake --project=test-software-dep-intake --location=europe-west3 --format="yaml(mode,remoteRepositoryConfig)" 
```

---

## List
```shell
gcloud artifacts repositories list --project=test-go-builder-authority --location=europe-west3 2>&1
```

---

## Create
```shell
cloud artifacts repositories create go-dependencies-intake --project=test-software-dep-intake --repository-format=go --location=europe-west3 --mode=remote-repository --remote-go-repo="https://proxy.golang.org/" --description="Go dependency intake remote upstream proxy.golang.org" --labels="boundary=dependency-authority,zone=intake" 2>&1
```
