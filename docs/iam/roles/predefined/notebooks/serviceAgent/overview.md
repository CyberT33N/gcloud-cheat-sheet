# `roles/notebooks.serviceAgent`

Provide access for notebooks service agent to manage notebook instances in user projects

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/notebooks.serviceAgent` |
| Title | AI Platform Notebooks Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 704 |
| Service | [notebooks](../overview.md) |

## Permissions

`roles/notebooks.serviceAgent` grants 704 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 16 |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [compute](permissions/compute/overview.md) | 581 |
| [dataproc](permissions/dataproc/overview.md) | 8 |
| [iam](permissions/iam/overview.md) | 4 |
| [ml](permissions/ml/overview.md) | 3 |
| [notebooks](permissions/notebooks/overview.md) | 59 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/notebooks.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
