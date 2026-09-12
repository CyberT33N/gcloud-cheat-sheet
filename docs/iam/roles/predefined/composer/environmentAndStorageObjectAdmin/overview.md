# `roles/composer.environmentAndStorageObjectAdmin`

Full control of Cloud Composer environments and Cloud Storage objects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/composer.environmentAndStorageObjectAdmin` |
| Title | Environment and Storage Object Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 75 |
| Service | [composer](../overview.md) |

## Permissions

`roles/composer.environmentAndStorageObjectAdmin` grants 75 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [composer](permissions/composer/overview.md) | 28 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 28 |

## Inspect this role live

```shell
gcloud iam roles describe roles/composer.environmentAndStorageObjectAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
