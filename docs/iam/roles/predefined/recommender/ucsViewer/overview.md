# `roles/recommender.ucsViewer`

Viewer of Spend Based Commitment Recommender.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/recommender.ucsViewer` |
| Title | Spend Based Commitment Recommender Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 9 |
| Service | [recommender](../overview.md) |

## Permissions

`roles/recommender.ucsViewer` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 2 |
| [recommender](permissions/recommender/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/recommender.ucsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
