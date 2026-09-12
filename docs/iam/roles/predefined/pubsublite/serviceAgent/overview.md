# `roles/pubsublite.serviceAgent`

Grants Pub/Sub Lite Service Agent access to project resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/pubsublite.serviceAgent` |
| Title | Pub/Sub Lite Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [pubsublite](../overview.md) |

## Permissions

`roles/pubsublite.serviceAgent` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [pubsublite](permissions/pubsublite/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/pubsublite.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
