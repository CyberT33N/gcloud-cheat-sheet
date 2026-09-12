# `roles/pubsub.subscriber`

Consume messages from a subscription, attach subscriptions to a topic, and seek to a snapshot.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/pubsub.subscriber` |
| Title | Pub/Sub Subscriber |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [pubsub](../overview.md) |

## Permissions

`roles/pubsub.subscriber` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [pubsub](permissions/pubsub/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/pubsub.subscriber --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
