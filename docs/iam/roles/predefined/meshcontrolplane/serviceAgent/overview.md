# `roles/meshcontrolplane.serviceAgent`

Anthos Service Mesh Managed Control Plane Agent

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/meshcontrolplane.serviceAgent` |
| Title | Mesh Managed Control Plane Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 457 |
| Service | [meshcontrolplane](../overview.md) |

## Permissions

`roles/meshcontrolplane.serviceAgent` grants 457 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [container](permissions/container/overview.md) | 405 |
| [gkehub](permissions/gkehub/overview.md) | 31 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/meshcontrolplane.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
