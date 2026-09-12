# `roles/datalineage.admin`

Grants full access to all resources in Data Lineage API

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datalineage.admin` |
| Title | Data Lineage Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [datalineage](../overview.md) |

## Permissions

`roles/datalineage.admin` grants 27 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datalineage](permissions/datalineage/overview.md) | 25 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datalineage.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
