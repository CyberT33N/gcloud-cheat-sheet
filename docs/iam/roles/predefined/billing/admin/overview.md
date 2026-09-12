# `roles/billing.admin`

Authorized to see and manage all aspects of billing accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/billing.admin` |
| Title | Billing Account Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 145 |
| Service | [billing](../overview.md) |

## Permissions

`roles/billing.admin` grants 145 permissions across 13 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 48 |
| [chroniclesm](permissions/chroniclesm/overview.md) | 2 |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [cloudsupport](permissions/cloudsupport/overview.md) | 6 |
| [commerceoffercatalog](permissions/commerceoffercatalog/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 5 |
| [consumerprocurement](permissions/consumerprocurement/overview.md) | 23 |
| [dataprocessing](permissions/dataprocessing/overview.md) | 4 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 4 |
| [logging](permissions/logging/overview.md) | 5 |
| [recommender](permissions/recommender/overview.md) | 37 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/billing.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
