# `roles/backupdr.backupvaultAccessor`

Allows the Backup Appliance permissions to create and manage backups in a backup vault.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.backupvaultAccessor` |
| Title | Backup and DR Backup Vault Accessor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.backupvaultAccessor` grants 19 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 19 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.backupvaultAccessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
