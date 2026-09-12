# `roles/healthcare.serviceAgent`

Gives the Healthcare Service Account access to networks, Kubernetes engine, and Pub/Sub resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/healthcare.serviceAgent` |
| Title | Healthcare Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 41 |
| Service | [healthcare](../overview.md) |

## Permissions

`roles/healthcare.serviceAgent` grants 41 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 31 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/healthcare.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
