# `roles/backupdr.managementServerAccessor`

Grants the Backup and DR management server access role to Backup Appliances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.managementServerAccessor` |
| Title | Backup and DR Management Server Accessor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.managementServerAccessor` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.managementServerAccessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
