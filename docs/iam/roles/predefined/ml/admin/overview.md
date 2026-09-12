# `roles/ml.admin`

Full access to AI Platform.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ml.admin` |
| Title | AI Platform Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 39 |
| Service | [ml](../overview.md) |

## Permissions

`roles/ml.admin` grants 39 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [ml](permissions/ml/overview.md) | 38 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ml.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
