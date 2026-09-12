# `roles/alloydb.editor`

Editor role for AlloyDB

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/alloydb.editor` |
| Title | AlloyDB Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 59 |
| Service | [alloydb](../overview.md) |

## Permissions

`roles/alloydb.editor` grants 59 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 48 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/alloydb.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
