# Projects 

## Read
```shell
gcloud logging read "resource.type=cloud_run_revision AND resource.labels.service_name=git-governance-release-broker AND resource.labels.revision_name=git-governance-release-broker-xxxxxxxx" --project=git-governance-release-broker --limit=50 --format="json(timestamp,severity,textPayload)"
```
