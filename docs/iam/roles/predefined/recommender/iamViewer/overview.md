# `roles/recommender.iamViewer`

Viewer of IAM recommendations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/recommender.iamViewer` |
| Title | IAM Recommender Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [recommender](../overview.md) |

## Permissions

`roles/recommender.iamViewer` grants 15 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [recommender](permissions/recommender/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securitycenter](permissions/securitycenter/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/recommender.iamViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
