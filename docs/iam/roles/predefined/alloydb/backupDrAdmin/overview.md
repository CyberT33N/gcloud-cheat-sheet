# `roles/alloydb.backupDrAdmin`

Full access to AlloyDB all clusters resources for BackupDR

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/alloydb.backupDrAdmin` |
| Title | AlloyDB Admin for BackupDR |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 25 |
| Service | [alloydb](../overview.md) |

## Permissions

`roles/alloydb.backupDrAdmin` grants 25 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 7 |
| [backupdr](permissions/backupdr/overview.md) | 18 |

## Inspect this role live

```shell
gcloud iam roles describe roles/alloydb.backupDrAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
