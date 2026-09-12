# `roles/retail.merchantApprover`

Grants access and approval rights to MerchantControls in the merchant console.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/retail.merchantApprover` |
| Title | Retail Merchant Approver |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 57 |
| Service | [retail](../overview.md) |

## Permissions

`roles/retail.merchantApprover` grants 57 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automlrecommendations](permissions/automlrecommendations/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [retail](permissions/retail/overview.md) | 45 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/retail.merchantApprover --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
