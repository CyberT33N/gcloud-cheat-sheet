# `roles/contentwarehouse.serviceAgent`

Gives the Content Warehouse service account to manage customer resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/contentwarehouse.serviceAgent` |
| Title | Content Warehouse Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [contentwarehouse](../overview.md) |

## Permissions

`roles/contentwarehouse.serviceAgent` grants 13 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 1 |
| [documentai](permissions/documentai/overview.md) | 3 |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [pubsublite](permissions/pubsublite/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/contentwarehouse.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
