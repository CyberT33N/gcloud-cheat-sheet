# `roles/alloydb.admin`

Full access to AlloyDB all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/alloydb.admin` |
| Title | AlloyDB Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 104 |
| Service | [alloydb](../overview.md) |

## Permissions

`roles/alloydb.admin` grants 104 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 52 |
| [backupdr](permissions/backupdr/overview.md) | 18 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 8 |
| [recommender](permissions/recommender/overview.md) | 18 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/alloydb.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
