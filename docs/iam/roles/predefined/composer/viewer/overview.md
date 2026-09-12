# `roles/composer.viewer`

Viewer role for Composer

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/composer.viewer` |
| Title | Composer Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [composer](../overview.md) |

## Permissions

`roles/composer.viewer` grants 16 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [composer](permissions/composer/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/composer.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
