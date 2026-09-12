# `roles/workloadmanager.insightWriter`

The role used to write data to WLM data warehouse.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workloadmanager.insightWriter` |
| Title | Workload Manager Insights Writer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 2 |
| Service | [workloadmanager](../overview.md) |

## Permissions

`roles/workloadmanager.insightWriter` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [workloadmanager](permissions/workloadmanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workloadmanager.insightWriter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
