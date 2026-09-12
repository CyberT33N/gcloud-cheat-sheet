# `roles/managedidentities.backupViewer`

Read-only access to Google Cloud Managed Identities Backup and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedidentities.backupViewer` |
| Title | Google Cloud Managed Identities Backup Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [managedidentities](../overview.md) |

## Permissions

`roles/managedidentities.backupViewer` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [managedidentities](permissions/managedidentities/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedidentities.backupViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
