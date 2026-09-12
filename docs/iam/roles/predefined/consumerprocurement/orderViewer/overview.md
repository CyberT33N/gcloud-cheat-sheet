# `roles/consumerprocurement.orderViewer`

Allows inspecting purchases

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/consumerprocurement.orderViewer` |
| Title | Consumer Procurement Order Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 21 |
| Service | [consumerprocurement](../overview.md) |

## Permissions

`roles/consumerprocurement.orderViewer` grants 21 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 4 |
| [commerceoffercatalog](permissions/commerceoffercatalog/overview.md) | 5 |
| [consumerprocurement](permissions/consumerprocurement/overview.md) | 10 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/consumerprocurement.orderViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
