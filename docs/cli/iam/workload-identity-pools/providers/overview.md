# IAM

## Workload Identity

### Pools

#### Providers

##### OIDC

- [create-oidc](create-oidc/overview.md)
- [update-oidc](update-oidc/overview.md)

##### Describe
```shell
gcloud iam workload-identity-pools providers describe github-gba-approved-promote --project=test-go-builder-authority --location=global --workload-identity-pool=github-go-builder-pool --format="yaml(name,state,attributeMapping,attributeCondition,oidc)"
```


##### List
```shell
gcloud iam workload-identity-pools providers list --workload-identity-pool=github-release-pool --project=git-governance-release-broker --location=global 2>&1
```