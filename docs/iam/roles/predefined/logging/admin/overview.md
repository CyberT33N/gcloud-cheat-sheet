# `roles/logging.admin`

Access to all logging permissions, and dependent permissions.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/logging.admin` |
| Title | Logging Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 80 |
| Service | [logging](../overview.md) |

## Permissions

`roles/logging.admin` grants 80 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 77 |
| [observability](permissions/observability/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/logging.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
