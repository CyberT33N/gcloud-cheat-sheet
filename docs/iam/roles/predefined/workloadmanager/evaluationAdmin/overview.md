# `roles/workloadmanager.evaluationAdmin`

Full access to Workload Manager evaluation resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workloadmanager.evaluationAdmin` |
| Title | Workload Manager Evaluation Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 22 |
| Service | [workloadmanager](../overview.md) |

## Permissions

`roles/workloadmanager.evaluationAdmin` grants 22 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [workloadmanager](permissions/workloadmanager/overview.md) | 19 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workloadmanager.evaluationAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
