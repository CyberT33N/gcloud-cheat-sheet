# `roles/iamconnectors.admin`

Grants access to manage connectors, authorizations, and access events.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iamconnectors.admin` |
| Title | Connector Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 38 |
| Service | [iamconnectors](../overview.md) |

## Permissions

`roles/iamconnectors.admin` grants 38 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [agentidentity](permissions/agentidentity/overview.md) | 17 |
| [iamconnectors](permissions/iamconnectors/overview.md) | 21 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iamconnectors.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
