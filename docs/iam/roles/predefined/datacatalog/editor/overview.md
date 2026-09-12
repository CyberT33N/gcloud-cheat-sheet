# `roles/datacatalog.editor`

Editor role for Data Catalog

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datacatalog.editor` |
| Title | Data Catalog Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 90 |
| Service | [datacatalog](../overview.md) |

## Permissions

`roles/datacatalog.editor` grants 90 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 5 |
| [datacatalog](permissions/datacatalog/overview.md) | 51 |
| [dataplex](permissions/dataplex/overview.md) | 31 |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datacatalog.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
