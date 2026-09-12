# `roles/kuberun.eventsDataPlaneServiceAgent`

Service account role used to setup authentication for the data plane used by KubeRun Events.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/kuberun.eventsDataPlaneServiceAgent` |
| Title | KubeRun Events Data Plane Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [kuberun](../overview.md) |

## Permissions

`roles/kuberun.eventsDataPlaneServiceAgent` grants 7 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtrace](permissions/cloudtrace/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/kuberun.eventsDataPlaneServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
