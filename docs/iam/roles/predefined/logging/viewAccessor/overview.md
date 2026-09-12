# `roles/logging.viewAccessor`

Ability to read logs in a view.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/logging.viewAccessor` |
| Title | Logs View Accessor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [logging](../overview.md) |

## Permissions

`roles/logging.viewAccessor` grants 5 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/logging.viewAccessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
