# `roles/gkebackup.delegatedRestoreAdmin`

Allows administrators to manage Restore resources for specific RestorePlans

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkebackup.delegatedRestoreAdmin` |
| Title | Backup for GKE Delegated Restore Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [gkebackup](../overview.md) |

## Permissions

`roles/gkebackup.delegatedRestoreAdmin` grants 8 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkebackup](permissions/gkebackup/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkebackup.delegatedRestoreAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
