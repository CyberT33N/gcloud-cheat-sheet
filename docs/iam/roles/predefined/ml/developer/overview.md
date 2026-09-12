# `roles/ml.developer`

Access to create training and prediction jobs, models and versions, send online prediction requests.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ml.developer` |
| Title | AI Platform Developer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 29 |
| Service | [ml](../overview.md) |

## Permissions

`roles/ml.developer` grants 29 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [ml](permissions/ml/overview.md) | 28 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ml.developer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
