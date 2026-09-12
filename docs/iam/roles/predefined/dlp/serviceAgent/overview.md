# `roles/dlp.serviceAgent`

Gives Cloud DLP service agent permissions for BigQuery, Cloud Storage, Datastore, Pub/Sub and Cloud KMS.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dlp.serviceAgent` |
| Title | DLP API Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 328 |
| Service | [dlp](../overview.md) |

## Permissions

`roles/dlp.serviceAgent` grants 328 permissions across 22 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [bigquery](permissions/bigquery/overview.md) | 79 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [cloudasset](permissions/cloudasset/overview.md) | 3 |
| [cloudkms](permissions/cloudkms/overview.md) | 3 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 6 |
| [datacatalog](permissions/datacatalog/overview.md) | 10 |
| [dataform](permissions/dataform/overview.md) | 5 |
| [dataplex](permissions/dataplex/overview.md) | 23 |
| [datastore](permissions/datastore/overview.md) | 14 |
| [dlp](permissions/dlp/overview.md) | 13 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [geminidataanalytics](permissions/geminidataanalytics/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 9 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 51 |
| [recommender](permissions/recommender/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 11 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dlp.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
