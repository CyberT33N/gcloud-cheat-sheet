# `roles/backupdr.user`

Provides access to management console. Granular Backup and DR permissions depend on ACL configuration provided by Backup and DR admin within the management console.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.user` |
| Title | Backup and DR User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.user` grants 23 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
