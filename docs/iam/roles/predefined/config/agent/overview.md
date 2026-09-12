# `roles/config.agent`

Required permissions to make Cloud Infrastructure Manager work with the user-specified service account

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/config.agent` |
| Title | Cloud Infrastructure Manager Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [config](../overview.md) |

## Permissions

`roles/config.agent` grants 23 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 3 |
| [cloudquotas](permissions/cloudquotas/overview.md) | 1 |
| [config](permissions/config/overview.md) | 7 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/config.agent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
