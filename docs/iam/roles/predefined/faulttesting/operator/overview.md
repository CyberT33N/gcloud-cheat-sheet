# `roles/faulttesting.operator`

Full access to Fault Testing resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/faulttesting.operator` |
| Title | Fault Testing Admin/Operator |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 26 |
| Service | [faulttesting](../overview.md) |

## Permissions

`roles/faulttesting.operator` grants 26 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [faulttesting](permissions/faulttesting/overview.md) | 24 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/faulttesting.operator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
