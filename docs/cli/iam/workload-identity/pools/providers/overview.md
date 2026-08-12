# IAM

## Workload Identity

### Pools

#### Providers

#####  OIDC
docs\cli\iam\workload-identity\pools\providers\oidc\overview.md


##### Describe
```shell
gcloud iam workload-identity-pools providers describe github-gba-approved-promote --project=test-go-builder-authority --location=global --workload-identity-pool=github-go-builder-pool --format="yaml(name,state,attributeMapping,attributeCondition,oidc)"
```