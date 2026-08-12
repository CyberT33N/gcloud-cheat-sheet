# IAM

## Workload Identity

### Pools

#### List
```shell
gcloud iam workload-identity-pools list --project=test-go-builder-authority --location=global --format="table(name,displayName,state)"
```

#### Create
```shell
gcloud iam workload-identity-pools create github-go-builder-pool --project=test-go-builder-authority --location=global --display-name="GitHub Go Builder Pool" --description="GitHub Actions federation boundary for Go Builder Authority" --quiet
```
