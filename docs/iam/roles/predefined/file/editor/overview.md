# `roles/file.editor`

Read-write access to Filestore instances and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/file.editor` |
| Title | Cloud Filestore Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 59 |
| Service | [file](../overview.md) |

## Permissions

`roles/file.editor` grants 59 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 17 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [file](permissions/file/overview.md) | 37 |

## Inspect this role live

```shell
gcloud iam roles describe roles/file.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
