# `roles/observability.viewAccessor`

Read only access to data defined by an Observability View.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/observability.viewAccessor` |
| Title | Observability View Accessor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 1 |
| Service | [observability](../overview.md) |

## Permissions

`roles/observability.viewAccessor` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [observability](permissions/observability/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/observability.viewAccessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
