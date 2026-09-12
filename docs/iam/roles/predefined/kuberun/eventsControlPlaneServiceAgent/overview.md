# `roles/kuberun.eventsControlPlaneServiceAgent`

Service account role used to setup authentication for the control plane used by KubeRun Events.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/kuberun.eventsControlPlaneServiceAgent` |
| Title | KubeRun Events Control Plane Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 18 |
| Service | [kuberun](../overview.md) |

## Permissions

`roles/kuberun.eventsControlPlaneServiceAgent` grants 18 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudscheduler](permissions/cloudscheduler/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 3 |
| [pubsub](permissions/pubsub/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/kuberun.eventsControlPlaneServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
