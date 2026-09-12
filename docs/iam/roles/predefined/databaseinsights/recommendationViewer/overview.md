# `roles/databaseinsights.recommendationViewer`

Viewer role for Database Insights recommendation data

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/databaseinsights.recommendationViewer` |
| Title | Database Insights recommendation viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [databaseinsights](../overview.md) |

## Permissions

`roles/databaseinsights.recommendationViewer` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [databaseinsights](permissions/databaseinsights/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/databaseinsights.recommendationViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
