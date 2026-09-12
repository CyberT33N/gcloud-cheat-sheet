# `roles/retail.viewer`

Grants access to read all resources in Retail.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/retail.viewer` |
| Title | Retail Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 42 |
| Service | [retail](../overview.md) |

## Permissions

`roles/retail.viewer` grants 42 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automlrecommendations](permissions/automlrecommendations/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [retail](permissions/retail/overview.md) | 31 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/retail.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
