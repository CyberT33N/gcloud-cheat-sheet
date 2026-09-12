# `roles/alloydb.viewer`

Read-only access to AlloyDB all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/alloydb.viewer` |
| Title | AlloyDB Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 33 |
| Service | [alloydb](../overview.md) |

## Permissions

`roles/alloydb.viewer` grants 33 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 22 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/alloydb.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
