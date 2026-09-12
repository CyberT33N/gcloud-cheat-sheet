# `roles/observability.analyticsUser`

Grants permissions to use Cloud Observability Analytics.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/observability.analyticsUser` |
| Title | Observability Analytics User |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 24 |
| Service | [observability](../overview.md) |

## Permissions

`roles/observability.analyticsUser` grants 24 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 3 |
| [observability](permissions/observability/overview.md) | 21 |

## Inspect this role live

```shell
gcloud iam roles describe roles/observability.analyticsUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
