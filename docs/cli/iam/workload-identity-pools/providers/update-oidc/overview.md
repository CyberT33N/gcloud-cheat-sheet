# update-oidc

```shell
gcloud iam workload-identity-pools providers update-oidc github-gba-staging-deploy --project=test-go-builder-authority --location=global --workload-identity-pool=github-go-builder-pool --disabled --attribute-mapping="google.subject=assertion.sub,attribute.repository=assertion.repository,attribute.repository_owner=assertion.repository_owner,attribute.ref=assertion.ref,attribute.environment=assertion.environment,attribute.lane='staging'" --quiet
```
