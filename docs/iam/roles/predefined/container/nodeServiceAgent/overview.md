# `roles/container.nodeServiceAgent`

Minimal set of permission required by a GKE node to support standard capabilities such as logging and monitoring export, and image pulls.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/container.nodeServiceAgent` |
| Title | [Deprecated] Kubernetes Engine Node Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [container](../overview.md) |

## Permissions

`roles/container.nodeServiceAgent` grants 11 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [autoscaling](permissions/autoscaling/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/container.nodeServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
