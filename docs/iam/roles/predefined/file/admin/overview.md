# `roles/file.admin`

Admin role for file

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/file.admin` |
| Title | File Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 61 |
| Service | [file](../overview.md) |

## Permissions

`roles/file.admin` grants 61 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 17 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [file](permissions/file/overview.md) | 37 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/file.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
