# `roles/chat.owner`

Can view and modify app configurations

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chat.owner` |
| Title | Chat Apps Owner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [chat](../overview.md) |

## Permissions

`roles/chat.owner` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [chat](permissions/chat/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chat.owner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
