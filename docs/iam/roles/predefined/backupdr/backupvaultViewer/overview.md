# `roles/backupdr.backupvaultViewer`

Allows read-only permissions to access backup vault resources and backups.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.backupvaultViewer` |
| Title | Backup and DR Backup Vault Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.backupvaultViewer` grants 8 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.backupvaultViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
