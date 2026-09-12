# `roles/dataform.admin`

Full access to all Dataform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataform.admin` |
| Title | Dataform Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 100 |
| Service | [dataform](../overview.md) |

## Permissions

`roles/dataform.admin` grants 100 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataform](permissions/dataform/overview.md) | 98 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataform.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
