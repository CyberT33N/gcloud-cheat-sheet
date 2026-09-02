# Repositories

[INTENT: REFERENCE]

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

---

## List with formatted table

```shell
gcloud artifacts repositories list --project=test-go-builder-authority --location=europe-west3 --format="table(name,format,mode,description)"
```

---

## Describe with docker config

```shell
gcloud artifacts repositories describe go-builder-staging-images --project=test-go-builder-authority --location=europe-west3 --format="yaml(name,format,dockerConfig,labels,vulnerabilityScanningConfig)"
```

---

## Create immutable docker repository

```shell
gcloud artifacts repositories create go-builder-approved-images --project=test-go-builder-authority --location=europe-west3 --repository-format=docker --immutable-tags --disable-vulnerability-scanning --description="Immutable approved Go builder images" --labels="authority=go_builder,lane=approved,subject=builder" --quiet
```

## Related

- [IAM Policy Binding](iam-policy-binding.md)
