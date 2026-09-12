# `roles/agentgateway.serviceAgent`

Grants Agent Gateway Service Agent permissions required to do DNS peering.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/agentgateway.serviceAgent` |
| Title | Agent Gateway Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [agentgateway](../overview.md) |

## Permissions

`roles/agentgateway.serviceAgent` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dns](permissions/dns/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/agentgateway.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
