# `roles/containerregistry.ServiceAgent`

Access for Container Registry

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/containerregistry.ServiceAgent` |
| Title | Container Registry Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [containerregistry](../overview.md) |

## Permissions

`roles/containerregistry.ServiceAgent` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/containerregistry.ServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
