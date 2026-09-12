# `roles/recommender.viewer`

Enables Get and List operations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/recommender.viewer` |
| Title | Recommender Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 291 |
| Service | [recommender](../overview.md) |

## Permissions

`roles/recommender.viewer` grants 291 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [recommender](permissions/recommender/overview.md) | 290 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/recommender.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
