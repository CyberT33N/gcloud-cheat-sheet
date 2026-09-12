# `roles/backupdr.cloudSqlOperator`

Allows a Backup and DR service account to discover and backup Cloud SQL instances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.cloudSqlOperator` |
| Title | Backup and DR Cloud SQL Operator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.cloudSqlOperator` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudsql](permissions/cloudsql/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.cloudSqlOperator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
