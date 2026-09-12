# `roles/datafusion.accessor`

Read-only access to Cloud Data Fusion Instances. Use it on instance level along with the namespace grants to provide access to the specific namespace.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datafusion.accessor` |
| Title | Cloud Data Fusion Accessor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 7 |
| Service | [datafusion](../overview.md) |

## Permissions

`roles/datafusion.accessor` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datafusion](permissions/datafusion/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datafusion.accessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
