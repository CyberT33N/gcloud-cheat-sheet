# `roles/file.viewer`

Read-only access to Filestore instances and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/file.viewer` |
| Title | Cloud Filestore Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 21 |
| Service | [file](../overview.md) |

## Permissions

`roles/file.viewer` grants 21 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 4 |
| [file](permissions/file/overview.md) | 17 |

## Inspect this role live

```shell
gcloud iam roles describe roles/file.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
