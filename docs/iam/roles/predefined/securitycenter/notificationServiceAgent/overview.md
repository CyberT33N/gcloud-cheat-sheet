# `roles/securitycenter.notificationServiceAgent`

Security Center service agent can publish notifications to Pub/Sub topics.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.notificationServiceAgent` |
| Title | Security Center Notification Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.notificationServiceAgent` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [pubsub](permissions/pubsub/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.notificationServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
