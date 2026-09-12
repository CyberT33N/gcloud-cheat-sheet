# `roles/workloadmanager.workloadViewer`

The role used to view the workload related data.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workloadmanager.workloadViewer` |
| Title | Workload Manager Workload Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 14 |
| Service | [workloadmanager](../overview.md) |

## Permissions

`roles/workloadmanager.workloadViewer` grants 14 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |
| [workloadmanager](permissions/workloadmanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workloadmanager.workloadViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
