# `roles/recommender.iamAdmin`

Admin of IAM recommendations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/recommender.iamAdmin` |
| Title | IAM Recommender Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [recommender](../overview.md) |

## Permissions

`roles/recommender.iamAdmin` grants 23 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [recommender](permissions/recommender/overview.md) | 16 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securitycenter](permissions/securitycenter/overview.md) | 2 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/recommender.iamAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
