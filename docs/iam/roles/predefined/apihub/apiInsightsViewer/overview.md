# `roles/apihub.apiInsightsViewer`

View API hub insights dashboards.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apihub.apiInsightsViewer` |
| Title | Cloud API hub Insights Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [apihub](../overview.md) |

## Permissions

`roles/apihub.apiInsightsViewer` grants 16 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 1 |
| [apihub](permissions/apihub/overview.md) | 9 |
| [monitoring](permissions/monitoring/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apihub.apiInsightsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
