# `roles/backupdr.admin`

Provides full access to all Backup and DR resources. 

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.admin` |
| Title | Backup and DR Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 159 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.admin` grants 159 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 152 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
