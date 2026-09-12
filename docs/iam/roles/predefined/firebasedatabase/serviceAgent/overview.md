# `roles/firebasedatabase.serviceAgent`

Access to publish triggers

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasedatabase.serviceAgent` |
| Title | Firebase Realtime Database Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [firebasedatabase](../overview.md) |

## Permissions

`roles/firebasedatabase.serviceAgent` grants 2 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasedatabase.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
