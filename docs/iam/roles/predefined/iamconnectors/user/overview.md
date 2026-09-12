# `roles/iamconnectors.user`

Grants access to retrieve credentials from connectors.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iamconnectors.user` |
| Title | Connector User |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 2 |
| Service | [iamconnectors](../overview.md) |

## Permissions

`roles/iamconnectors.user` grants 2 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [agentidentity](permissions/agentidentity/overview.md) | 1 |
| [iamconnectors](permissions/iamconnectors/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iamconnectors.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
