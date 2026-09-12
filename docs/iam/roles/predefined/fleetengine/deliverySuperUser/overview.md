# `roles/fleetengine.deliverySuperUser`

Full access to Fleet Engine DeliveryVehicles and Tasks resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/fleetengine.deliverySuperUser` |
| Title | Fleet Engine Delivery Super User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [fleetengine](../overview.md) |

## Permissions

`roles/fleetengine.deliverySuperUser` grants 16 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [fleetengine](permissions/fleetengine/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/fleetengine.deliverySuperUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
