# `roles/consumerprocurement.orderAdmin`

Allows managing purchases

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/consumerprocurement.orderAdmin` |
| Title | Consumer Procurement Order Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 38 |
| Service | [consumerprocurement](../overview.md) |

## Permissions

`roles/consumerprocurement.orderAdmin` grants 38 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 6 |
| [commerceoffercatalog](permissions/commerceoffercatalog/overview.md) | 5 |
| [consumerprocurement](permissions/consumerprocurement/overview.md) | 23 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/consumerprocurement.orderAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
