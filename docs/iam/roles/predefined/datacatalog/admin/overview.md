# `roles/datacatalog.admin`

Full access to all DataCatalog resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datacatalog.admin` |
| Title | Data Catalog Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 180 |
| Service | [datacatalog](../overview.md) |

## Permissions

`roles/datacatalog.admin` grants 180 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 10 |
| [datacatalog](permissions/datacatalog/overview.md) | 59 |
| [dataplex](permissions/dataplex/overview.md) | 107 |
| [pubsub](permissions/pubsub/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datacatalog.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
