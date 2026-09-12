# `roles/iamconnectors.viewer`

Grants access to view connectors, authorizations, and access events.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iamconnectors.viewer` |
| Title | Connector Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 22 |
| Service | [iamconnectors](../overview.md) |

## Permissions

`roles/iamconnectors.viewer` grants 22 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [agentidentity](permissions/agentidentity/overview.md) | 10 |
| [iamconnectors](permissions/iamconnectors/overview.md) | 12 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iamconnectors.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
