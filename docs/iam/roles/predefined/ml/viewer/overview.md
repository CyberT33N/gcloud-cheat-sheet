# `roles/ml.viewer`

Read-only access to AI Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ml.viewer` |
| Title | AI Platform Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [ml](../overview.md) |

## Permissions

`roles/ml.viewer` grants 17 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [ml](permissions/ml/overview.md) | 16 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ml.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
