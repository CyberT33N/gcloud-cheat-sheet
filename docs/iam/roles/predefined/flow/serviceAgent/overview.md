# `roles/flow.serviceAgent`

Grants Flow Service Agent permissions to manage resources in the consumer project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/flow.serviceAgent` |
| Title | Flow Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 6 |
| Service | [flow](../overview.md) |

## Permissions

`roles/flow.serviceAgent` grants 6 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/flow.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
