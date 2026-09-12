# `roles/backupdr.backupConfigViewer`

Provides read access to resource backup config. Resource backup config has the metadata of a Google Cloud resource that can be backed up, along with its backup configurations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/backupdr.backupConfigViewer` |
| Title | Backup and DR Backup Config Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [backupdr](../overview.md) |

## Permissions

`roles/backupdr.backupConfigViewer` grants 4 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/backupdr.backupConfigViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
