# `roles/consumerprocurement.entitlementManager`

Allows managing entitlements and enabling, disabling, and inspecting service states for a consumer project

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/consumerprocurement.entitlementManager` |
| Title | Consumer Procurement Entitlement Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 26 |
| Service | [consumerprocurement](../overview.md) |

## Permissions

`roles/consumerprocurement.entitlementManager` grants 26 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [commerceoffercatalog](permissions/commerceoffercatalog/overview.md) | 1 |
| [consumerprocurement](permissions/consumerprocurement/overview.md) | 9 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/consumerprocurement.entitlementManager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
