# `roles/meshdataplane.serviceAgent`

Run user-space Istio components

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/meshdataplane.serviceAgent` |
| Title | Mesh Data Plane Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [meshdataplane](../overview.md) |

## Permissions

`roles/meshdataplane.serviceAgent` grants 13 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtrace](permissions/cloudtrace/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [telemetry](permissions/telemetry/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/meshdataplane.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
