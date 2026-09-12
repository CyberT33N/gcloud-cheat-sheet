# `roles/agentidentity.user`

Grants access to retrieve and exchange credentials from auth providers and authorizations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/agentidentity.user` |
| Title | Agent Identity User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [agentidentity](../overview.md) |

## Permissions

`roles/agentidentity.user` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [agentidentity](permissions/agentidentity/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/agentidentity.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
