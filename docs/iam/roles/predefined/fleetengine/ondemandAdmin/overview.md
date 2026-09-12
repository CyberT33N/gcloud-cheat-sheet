# `roles/fleetengine.ondemandAdmin`

Full access to Vehicle and Trip resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/fleetengine.ondemandAdmin` |
| Title | Fleet Engine On-Demand Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [fleetengine](../overview.md) |

## Permissions

`roles/fleetengine.ondemandAdmin` grants 19 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [fleetengine](permissions/fleetengine/overview.md) | 16 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/fleetengine.ondemandAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
