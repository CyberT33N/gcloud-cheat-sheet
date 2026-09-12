# `roles/datamigration.serviceAgent`

Gives Cloud Database Migration service account access to Cloud SQL resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datamigration.serviceAgent` |
| Title | Database Migration Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 85 |
| Service | [datamigration](../overview.md) |

## Permissions

`roles/datamigration.serviceAgent` grants 85 permissions across 8 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 20 |
| [cloudsql](permissions/cloudsql/overview.md) | 24 |
| [compute](permissions/compute/overview.md) | 26 |
| [datamigration](permissions/datamigration/overview.md) | 6 |
| [logging](permissions/logging/overview.md) | 4 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datamigration.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
