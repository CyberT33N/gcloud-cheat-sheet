# `roles/billing.linkAdmin`

Authorized to manage billing account hierarchy

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/billing.linkAdmin` |
| Title | Account Hierarchy Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 62 |
| Service | [billing](../overview.md) |

## Permissions

`roles/billing.linkAdmin` grants 62 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 32 |
| [commerceoffercatalog](permissions/commerceoffercatalog/overview.md) | 5 |
| [consumerprocurement](permissions/consumerprocurement/overview.md) | 8 |
| [dataprocessing](permissions/dataprocessing/overview.md) | 4 |
| [recommender](permissions/recommender/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/billing.linkAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
