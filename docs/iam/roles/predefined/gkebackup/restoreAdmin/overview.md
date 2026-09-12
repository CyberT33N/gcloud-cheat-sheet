# `roles/gkebackup.restoreAdmin`

Allows administrators to manage all RestorePlan and Restore resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkebackup.restoreAdmin` |
| Title | Backup for GKE Restore Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 31 |
| Service | [gkebackup](../overview.md) |

## Permissions

`roles/gkebackup.restoreAdmin` grants 31 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkebackup](permissions/gkebackup/overview.md) | 29 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkebackup.restoreAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
