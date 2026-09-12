# `roles/datafusion.operator`

Access Cloud Data Fusion Instances, operate namespaces and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datafusion.operator` |
| Title | Cloud Data Fusion Operator |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 45 |
| Service | [datafusion](../overview.md) |

## Permissions

`roles/datafusion.operator` grants 45 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datafusion](permissions/datafusion/overview.md) | 43 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datafusion.operator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
