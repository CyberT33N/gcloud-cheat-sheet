# `roles/datafusion.admin`

Full access to Cloud Data Fusion Instances, Namespaces and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datafusion.admin` |
| Title | Cloud Data Fusion Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 63 |
| Service | [datafusion](../overview.md) |

## Permissions

`roles/datafusion.admin` grants 63 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datafusion](permissions/datafusion/overview.md) | 61 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datafusion.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
