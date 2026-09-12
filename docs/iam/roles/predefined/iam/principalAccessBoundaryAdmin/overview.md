# `roles/iam.principalAccessBoundaryAdmin`

Principal Access Boundary admin role, with permissions to read and modify principal access boundary policies, and to bind and unbind principal access boundary policies to targets. Also includes permissions to read principal authorization activities analysis and permissions to list assets from Cloud Asset Inventory

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.principalAccessBoundaryAdmin` |
| Title | Principal Access Boundary Policy Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.principalAccessBoundaryAdmin` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 2 |
| [iam](permissions/iam/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.principalAccessBoundaryAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
