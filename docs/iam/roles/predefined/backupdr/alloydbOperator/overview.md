# `roles/backupdr.alloydbOperator`

Allows a Backup and DR service account to discover and backup AlloyDB clusters.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.alloydbOperator` |
| Title | Backup and DR AlloyDB Operator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.alloydbOperator` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.alloydbOperator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
