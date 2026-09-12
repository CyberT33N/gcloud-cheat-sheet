# `roles/backupdr.diskOperator`

Allows a Backup and DR service account to store and manage data (backups or metadata) in Disk.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.diskOperator` |
| Title | Backup and DR Disk Operator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.diskOperator` grants 13 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.diskOperator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
