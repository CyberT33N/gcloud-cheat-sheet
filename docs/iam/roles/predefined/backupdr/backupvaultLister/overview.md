# `roles/backupdr.backupvaultLister`

Allows the Backup Appliance permission to list backup vaults in a given project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.backupvaultLister` |
| Title | Backup and DR Backup Vault Lister |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.backupvaultLister` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.backupvaultLister --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
