# `roles/health.viewer`

Read-only access to Google Health API resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/health.viewer` |
| Title | Google Health API Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [health](../overview.md) |

## Permissions

`roles/health.viewer` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [health](permissions/health/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/health.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
