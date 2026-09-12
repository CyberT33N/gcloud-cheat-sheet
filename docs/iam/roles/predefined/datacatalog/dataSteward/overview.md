# `roles/datacatalog.dataSteward`

Can update overview and data steward fields

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datacatalog.dataSteward` |
| Title | DataCatalog Data Steward |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 15 |
| Service | [datacatalog](../overview.md) |

## Permissions

`roles/datacatalog.dataSteward` grants 15 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datacatalog](permissions/datacatalog/overview.md) | 7 |
| [dataplex](permissions/dataplex/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datacatalog.dataSteward --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
