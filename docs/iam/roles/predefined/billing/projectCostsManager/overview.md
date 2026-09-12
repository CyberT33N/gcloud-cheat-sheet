# `roles/billing.projectCostsManager`

Can interact with billing information scoped to the projects to which the user has cost access.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/billing.projectCostsManager` |
| Title | Project Billing Costs Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [billing](../overview.md) |

## Permissions

`roles/billing.projectCostsManager` grants 4 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/billing.projectCostsManager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
