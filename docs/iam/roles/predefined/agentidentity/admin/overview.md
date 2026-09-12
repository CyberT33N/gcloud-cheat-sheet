# `roles/agentidentity.admin`

Grants access to manage auth providers, authorizations, and access summaries.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/agentidentity.admin` |
| Title | Agent Identity Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [agentidentity](../overview.md) |

## Permissions

`roles/agentidentity.admin` grants 17 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [agentidentity](permissions/agentidentity/overview.md) | 17 |

## Inspect this role live

```shell
gcloud iam roles describe roles/agentidentity.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
