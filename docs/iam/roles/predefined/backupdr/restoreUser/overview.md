# `roles/backupdr.restoreUser`

Allows the user to restore or mount from a backup. This role cannot create a backup plan.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.restoreUser` |
| Title | Backup and DR Restore User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 53 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.restoreUser` grants 53 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 51 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.restoreUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
