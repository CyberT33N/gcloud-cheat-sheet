# `roles/backupdr.cloudStorageOperator`

Allows a Backup and DR service account to store and manage data (backups or metadata) in Cloud Storage.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.cloudStorageOperator` |
| Title | Backup and DR Cloud Storage Operator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 6 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.cloudStorageOperator` grants 6 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.cloudStorageOperator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
