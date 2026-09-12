# `roles/consumerprocurement.procurementViewer`

Allows inspecting purchases, consents and entitlements and service states for a consumer project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/consumerprocurement.procurementViewer` |
| Title | Consumer Procurement Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 37 |
| Service | [consumerprocurement](../overview.md) |

## Permissions

`roles/consumerprocurement.procurementViewer` grants 37 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 4 |
| [commerceoffercatalog](permissions/commerceoffercatalog/overview.md) | 5 |
| [consumerprocurement](permissions/consumerprocurement/overview.md) | 14 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/consumerprocurement.procurementViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
