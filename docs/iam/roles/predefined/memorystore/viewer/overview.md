# `roles/memorystore.viewer`

Readonly access to Memorystore resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/memorystore.viewer` |
| Title | Memorystore Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [memorystore](../overview.md) |

## Permissions

`roles/memorystore.viewer` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [memorystore](permissions/memorystore/overview.md) | 10 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/memorystore.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
