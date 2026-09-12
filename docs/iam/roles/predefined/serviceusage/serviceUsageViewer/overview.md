# `roles/serviceusage.serviceUsageViewer`

Ability to inspect service states and operations for a consumer project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/serviceusage.serviceUsageViewer` |
| Title | Service Usage Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [serviceusage](../overview.md) |

## Permissions

`roles/serviceusage.serviceUsageViewer` grants 15 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 14 |

## Inspect this role live

```shell
gcloud iam roles describe roles/serviceusage.serviceUsageViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
