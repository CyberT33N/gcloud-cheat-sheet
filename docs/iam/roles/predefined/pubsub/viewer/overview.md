# `roles/pubsub.viewer`

View topics, subscriptions, and snapshots.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/pubsub.viewer` |
| Title | Pub/Sub Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 28 |
| Service | [pubsub](../overview.md) |

## Permissions

`roles/pubsub.viewer` grants 28 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [pubsub](permissions/pubsub/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/pubsub.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
