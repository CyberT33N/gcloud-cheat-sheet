# `roles/container.defaultNodeServiceAgent`

Minimal set of permissions required by a GKE node to support standard capabilities such as logging and monitoring. Replaces the container.nodeServiceAgent role with a reduced permission set.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/container.defaultNodeServiceAgent` |
| Title | Kubernetes Engine Default Node Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [container](../overview.md) |

## Permissions

`roles/container.defaultNodeServiceAgent` grants 10 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [autoscaling](permissions/autoscaling/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 4 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [telemetry](permissions/telemetry/overview.md) | 1 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/container.defaultNodeServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
