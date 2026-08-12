# IAM

## Workload Identity

### Pools

#### List#
```shell
gcloud iam workload-identity-pools list --project=test-go-builder-authority --location=global --format="table(name,displayName,state)"
```