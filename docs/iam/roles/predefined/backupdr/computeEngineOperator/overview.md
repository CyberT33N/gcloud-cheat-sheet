# `roles/backupdr.computeEngineOperator`

Allows a Backup and DR service account to discover, back up, and restore Compute Engine VM instances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.computeEngineOperator` |
| Title | Backup and DR Compute Engine Operator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 64 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.computeEngineOperator` grants 64 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 58 |
| [iam](permissions/iam/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.computeEngineOperator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
