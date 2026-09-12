# `roles/cloudmigration.storageaccess`

Ability to access migration storage

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudmigration.storageaccess` |
| Title | Velostrata Storage Access |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 5 |
| Service | [cloudmigration](../overview.md) |

## Permissions

`roles/cloudmigration.storageaccess` grants 5 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [storage](permissions/storage/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudmigration.storageaccess --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
