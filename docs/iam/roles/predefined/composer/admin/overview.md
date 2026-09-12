# `roles/composer.admin`

Full control of Composer resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/composer.admin` |
| Title | Composer Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 43 |
| Service | [composer](../overview.md) |

## Permissions

`roles/composer.admin` grants 43 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [composer](permissions/composer/overview.md) | 28 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/composer.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
