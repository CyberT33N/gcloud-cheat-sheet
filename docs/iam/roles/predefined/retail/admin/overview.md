# `roles/retail.admin`

Full access to Retail api resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/retail.admin` |
| Title | Retail Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 106 |
| Service | [retail](../overview.md) |

## Permissions

`roles/retail.admin` grants 106 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automlrecommendations](permissions/automlrecommendations/overview.md) | 25 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [retail](permissions/retail/overview.md) | 78 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/retail.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
