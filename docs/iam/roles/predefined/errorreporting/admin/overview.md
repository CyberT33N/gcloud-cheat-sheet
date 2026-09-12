# `roles/errorreporting.admin`

Administrative access to Error Reporting.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/errorreporting.admin` |
| Title | Error Reporting Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 16 |
| Service | [errorreporting](../overview.md) |

## Permissions

`roles/errorreporting.admin` grants 16 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [errorreporting](permissions/errorreporting/overview.md) | 7 |
| [logging](permissions/logging/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [stackdriver](permissions/stackdriver/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/errorreporting.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
