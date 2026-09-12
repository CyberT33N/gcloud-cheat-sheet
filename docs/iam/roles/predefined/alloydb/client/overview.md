# `roles/alloydb.client`

Connectivity access to AlloyDB instances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/alloydb.client` |
| Title | AlloyDB Client |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [alloydb](../overview.md) |

## Permissions

`roles/alloydb.client` grants 7 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 4 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/alloydb.client --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
