# `roles/workflows.invoker`

Access to execute workflows and manage the executions using the API. Does not provide access to develop and debug workflows.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workflows.invoker` |
| Title | Workflows Invoker |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [workflows](../overview.md) |

## Permissions

`roles/workflows.invoker` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [workflows](permissions/workflows/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workflows.invoker --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
