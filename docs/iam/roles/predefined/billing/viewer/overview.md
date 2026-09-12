# `roles/billing.viewer`

Can view information about billing accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/billing.viewer` |
| Title | Billing Account Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 62 |
| Service | [billing](../overview.md) |

## Permissions

`roles/billing.viewer` grants 62 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 29 |
| [chroniclesm](permissions/chroniclesm/overview.md) | 1 |
| [commerceoffercatalog](permissions/commerceoffercatalog/overview.md) | 5 |
| [consumerprocurement](permissions/consumerprocurement/overview.md) | 8 |
| [dataprocessing](permissions/dataprocessing/overview.md) | 4 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 2 |
| [recommender](permissions/recommender/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/billing.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
