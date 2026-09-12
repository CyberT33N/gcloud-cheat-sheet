# `roles/billing.costsManager`

Can view and export cost information of billing accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/billing.costsManager` |
| Title | Billing Account Costs Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [billing](../overview.md) |

## Permissions

`roles/billing.costsManager` grants 19 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 16 |
| [recommender](permissions/recommender/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/billing.costsManager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
