# `roles/storageinsights.serviceAgent`

Permissions for Insights to write reports into customer project

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storageinsights.serviceAgent` |
| Title | StorageInsights Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [storageinsights](../overview.md) |

## Permissions

`roles/storageinsights.serviceAgent` grants 3 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storageinsights](permissions/storageinsights/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storageinsights.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
