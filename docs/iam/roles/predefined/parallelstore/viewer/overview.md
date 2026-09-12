# `roles/parallelstore.viewer`

Readonly access to Parallelstore resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/parallelstore.viewer` |
| Title | Parallelstore Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [parallelstore](../overview.md) |

## Permissions

`roles/parallelstore.viewer` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [parallelstore](permissions/parallelstore/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/parallelstore.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
