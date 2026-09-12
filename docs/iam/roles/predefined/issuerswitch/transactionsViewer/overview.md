# `roles/issuerswitch.transactionsViewer`

This role can view all transactions

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/issuerswitch.transactionsViewer` |
| Title | Issuerswitch Transactions Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 8 |
| Service | [issuerswitch](../overview.md) |

## Permissions

`roles/issuerswitch.transactionsViewer` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [issuerswitch](permissions/issuerswitch/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/issuerswitch.transactionsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
