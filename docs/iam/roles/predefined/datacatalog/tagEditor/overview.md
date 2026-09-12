# `roles/datacatalog.tagEditor`

Gives permission to modify tags on a GCP assets (BigQuery, Pub/Sub etc).

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datacatalog.tagEditor` |
| Title | Data Catalog Tag Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [datacatalog](../overview.md) |

## Permissions

`roles/datacatalog.tagEditor` grants 9 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 5 |
| [datacatalog](permissions/datacatalog/overview.md) | 2 |
| [dataplex](permissions/dataplex/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datacatalog.tagEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
