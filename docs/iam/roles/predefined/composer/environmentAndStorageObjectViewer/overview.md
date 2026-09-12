# `roles/composer.environmentAndStorageObjectViewer`

Read access to Cloud Composer environments and Cloud Storage objects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/composer.environmentAndStorageObjectViewer` |
| Title | Environment and Storage Object Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 31 |
| Service | [composer](../overview.md) |

## Permissions

`roles/composer.environmentAndStorageObjectViewer` grants 31 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [composer](permissions/composer/overview.md) | 13 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/composer.environmentAndStorageObjectViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
