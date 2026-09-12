# `roles/backupdr.serviceAgent`

Grants the Backup and DR Service access to discover and protect GCP resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.serviceAgent` |
| Title | Backup and DR Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 82 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.serviceAgent` grants 82 permissions across 8 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 1 |
| [backupdr](permissions/backupdr/overview.md) | 7 |
| [cloudsql](permissions/cloudsql/overview.md) | 2 |
| [compute](permissions/compute/overview.md) | 60 |
| [file](permissions/file/overview.md) | 4 |
| [iam](permissions/iam/overview.md) | 3 |
| [netapp](permissions/netapp/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
