# `roles/backupdr.backupUser`

Allows the user to apply existing backup plans. This role cannot create backup plans or restore from a backup.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.backupUser` |
| Title | Backup and DR Backup User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 79 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.backupUser` grants 79 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 77 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.backupUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
