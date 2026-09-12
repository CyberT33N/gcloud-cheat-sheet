# `roles/remotebuildexecution.serviceAgent`

Gives Remote Build Execution service account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/remotebuildexecution.serviceAgent` |
| Title | Remote Build Execution Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [remotebuildexecution](../overview.md) |

## Permissions

`roles/remotebuildexecution.serviceAgent` grants 7 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/remotebuildexecution.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
