# `roles/composer.environmentAndStorageObjectUser`

Read and use access to Cloud Composer resources and read access Cloud Storage objects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/composer.environmentAndStorageObjectUser` |
| Title | Environment and Storage Object User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 31 |
| Service | [composer](../overview.md) |

## Permissions

`roles/composer.environmentAndStorageObjectUser` grants 31 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [composer](permissions/composer/overview.md) | 13 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/composer.environmentAndStorageObjectUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
