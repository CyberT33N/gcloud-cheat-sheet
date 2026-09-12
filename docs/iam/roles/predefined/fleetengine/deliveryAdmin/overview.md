# `roles/fleetengine.deliveryAdmin`

Full access to Fleet Engine Delivery resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/fleetengine.deliveryAdmin` |
| Title | Fleet Engine Delivery Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [fleetengine](../overview.md) |

## Permissions

`roles/fleetengine.deliveryAdmin` grants 20 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [fleetengine](permissions/fleetengine/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/fleetengine.deliveryAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
