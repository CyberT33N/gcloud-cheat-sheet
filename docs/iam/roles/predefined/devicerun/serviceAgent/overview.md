# `roles/devicerun.serviceAgent`

Grants Device Run Service Agent permissions required to manage resources in the consumer project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/devicerun.serviceAgent` |
| Title | Device Run Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [devicerun](../overview.md) |

## Permissions

`roles/devicerun.serviceAgent` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/devicerun.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
