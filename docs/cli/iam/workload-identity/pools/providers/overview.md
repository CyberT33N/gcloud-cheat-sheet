# IAM

## Workload Identity

### Pools

#### Providers

#####  Create OIDC
```shell
gcloud iam workload-identity-pools providers create-oidc github-gba-staging-deploy --project=test-go-builder-authority --location=global --workload-identity-pool=github-go-builder-pool --display-name="GBA Staging Deploy" --description="Disabled until reviewed staging workflow and GitHub environment exist" --disabled --issuer-uri=https://token.actions.githubusercontent.com --attribute-mapping="google.subject=assertion.sub,attribute.repository=assertion.repository,attribute.repository_owner=assertion.repository_owner,attribute.ref=assertion.ref,attribute.environment=assertion.environment" --attribute-condition="assertion.repository == 'CyberT33N/go-builder-authority' && assertion.repository_owner == 'CyberT33N' && assertion.ref == 'refs/heads/develop' && assertion.environment == 'gcp-go-builder-staging'" --quiet
```