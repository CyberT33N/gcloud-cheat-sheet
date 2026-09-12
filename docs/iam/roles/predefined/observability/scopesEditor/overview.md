# `roles/observability.scopesEditor`

Grants permission to view and edit Observability, Logging, Trace, and Monitoring scopes

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/observability.scopesEditor` |
| Title | Observability Scopes Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 13 |
| Service | [observability](../overview.md) |

## Permissions

`roles/observability.scopesEditor` grants 13 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 5 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [observability](permissions/observability/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/observability.scopesEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
