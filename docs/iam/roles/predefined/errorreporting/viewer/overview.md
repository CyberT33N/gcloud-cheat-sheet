# `roles/errorreporting.viewer`

Read-only access to all Error Reporting data.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/errorreporting.viewer` |
| Title | Error Reporting Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 10 |
| Service | [errorreporting](../overview.md) |

## Permissions

`roles/errorreporting.viewer` grants 10 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [errorreporting](permissions/errorreporting/overview.md) | 4 |
| [logging](permissions/logging/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [stackdriver](permissions/stackdriver/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/errorreporting.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
