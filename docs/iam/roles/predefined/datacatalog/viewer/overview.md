# `roles/datacatalog.viewer`

Grants metadata read permissions to cataloged GCP assets (BigQuery, Pub/Sub etc)

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datacatalog.viewer` |
| Title | Data Catalog Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 50 |
| Service | [datacatalog](../overview.md) |

## Permissions

`roles/datacatalog.viewer` grants 50 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 5 |
| [datacatalog](permissions/datacatalog/overview.md) | 11 |
| [dataplex](permissions/dataplex/overview.md) | 31 |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datacatalog.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
