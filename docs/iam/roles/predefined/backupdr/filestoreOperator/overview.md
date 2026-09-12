# `roles/backupdr.filestoreOperator`

Allows a Backup and DR service account to discover and backup Filestore instances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.filestoreOperator` |
| Title | Backup and DR Filestore Operator |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 3 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.filestoreOperator` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [file](permissions/file/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.filestoreOperator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
