# `roles/recommender.errorReportingViewer`

Viewer of Error Reporting Insights and Recommendations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/recommender.errorReportingViewer` |
| Title | Error Reporting Recommender Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [recommender](../overview.md) |

## Permissions

`roles/recommender.errorReportingViewer` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [recommender](permissions/recommender/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/recommender.errorReportingViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
