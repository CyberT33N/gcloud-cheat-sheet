# `roles/cloudsql.viewer`

Read-only access to Cloud SQL resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsql.viewer` |
| Title | Cloud SQL Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 67 |
| Service | [cloudsql](../overview.md) |

## Permissions

`roles/cloudsql.viewer` grants 67 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [cloudsql](permissions/cloudsql/overview.md) | 23 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 30 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsql.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
