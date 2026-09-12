# `roles/gkebackup.delegatedBackupAdmin`

Allows administrators to manage Backup resources for specific BackupPlans

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkebackup.delegatedBackupAdmin` |
| Title | Backup for GKE Delegated Backup Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [gkebackup](../overview.md) |

## Permissions

`roles/gkebackup.delegatedBackupAdmin` grants 13 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkebackup](permissions/gkebackup/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkebackup.delegatedBackupAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
