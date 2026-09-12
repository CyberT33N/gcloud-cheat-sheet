# `roles/connectors.eventSubscriptionViewer`

Event Subscription is a regional resource which creates subscriptions on events for a given connection within the given target project. This role grants Read-only access to Event Subscription resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/connectors.eventSubscriptionViewer` |
| Title | Connectors Event Subscriptions Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [connectors](../overview.md) |

## Permissions

`roles/connectors.eventSubscriptionViewer` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [connectors](permissions/connectors/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/connectors.eventSubscriptionViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
