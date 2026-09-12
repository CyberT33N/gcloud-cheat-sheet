# `roles/recommender.projectUtilAdmin`

Admin of Project Utilization insights and recommendations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/recommender.projectUtilAdmin` |
| Title | Project Utilization Recommender Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [recommender](../overview.md) |

## Permissions

`roles/recommender.projectUtilAdmin` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [recommender](permissions/recommender/overview.md) | 10 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/recommender.projectUtilAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
