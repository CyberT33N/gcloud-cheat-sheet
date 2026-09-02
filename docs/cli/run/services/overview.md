# Run Services

[INTENT: REFERENCE]

Manage Cloud Run services via `gcloud run services`.

## List

```shell
gcloud run services list --project=git-governance-release-broker --region=europe-west3 2>&1; gcloud artifacts repositories list --project=git-governance-release-broker --location=europe-west3 2>&1
```

## Describe

```shell
gcloud run services describe git-governance-release-broker --project=git-governance-release-broker --region=europe-west3 --format="yaml(spec.template.spec.containers[0].env)" 2>&1
```

## Update

```shell
gcloud run services update git-governance-release-broker --region=europe-west3 --project=git-governance-release-broker --update-env-vars "BROKER_ALLOWED_REPOSITORIES=github.com/test-software/git-governance,BROKER_APP_INSTALLATION_ID=xxxxxxxxxxxxxxx"
```
