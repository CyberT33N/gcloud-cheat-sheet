# `roles/iamconnectors.editor`

Grants access to edit connectors, authorizations, and access events.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iamconnectors.editor` |
| Title | Connector Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 36 |
| Service | [iamconnectors](../overview.md) |

## Permissions

`roles/iamconnectors.editor` grants 36 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [agentidentity](permissions/agentidentity/overview.md) | 16 |
| [iamconnectors](permissions/iamconnectors/overview.md) | 20 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iamconnectors.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
