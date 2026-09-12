# `roles/connectors.serviceAgent`

Grants Connectors Platform service account to manage customer resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/connectors.serviceAgent` |
| Title | Connectors Platform Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 35 |
| Service | [connectors](../overview.md) |

## Permissions

`roles/connectors.serviceAgent` grants 35 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [connectors](permissions/connectors/overview.md) | 26 |
| [iam](permissions/iam/overview.md) | 3 |
| [monitoring](permissions/monitoring/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/connectors.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
