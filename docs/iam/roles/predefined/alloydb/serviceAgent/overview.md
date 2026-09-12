# `roles/alloydb.serviceAgent`

Gives the AlloyDB service account permission to manage customer resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/alloydb.serviceAgent` |
| Title | AlloyDB Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [alloydb](../overview.md) |

## Permissions

`roles/alloydb.serviceAgent` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/alloydb.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
