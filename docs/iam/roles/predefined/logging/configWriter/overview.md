# `roles/logging.configWriter`

Access to configure log exporting and metrics.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/logging.configWriter` |
| Title | Logs Configuration Writer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 60 |
| Service | [logging](../overview.md) |

## Permissions

`roles/logging.configWriter` grants 60 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 57 |
| [observability](permissions/observability/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/logging.configWriter --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
