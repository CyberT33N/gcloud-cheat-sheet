# `roles/backupdr.userv2`

Provides full access to Backup and DR resources except deploying and managing backup infrastructure, expiring backups, changing data sensitivity and configuring on-premises billing.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.userv2` |
| Title | Backup and DR User V2 |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 116 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.userv2` grants 116 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 114 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.userv2 --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
