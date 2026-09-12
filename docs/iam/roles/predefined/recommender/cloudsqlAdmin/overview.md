# `roles/recommender.cloudsqlAdmin`

Admin of Cloud SQL insights and recommendations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/recommender.cloudsqlAdmin` |
| Title | Cloud SQL Recommender Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 53 |
| Service | [recommender](../overview.md) |

## Permissions

`roles/recommender.cloudsqlAdmin` grants 53 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [recommender](permissions/recommender/overview.md) | 51 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/recommender.cloudsqlAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
