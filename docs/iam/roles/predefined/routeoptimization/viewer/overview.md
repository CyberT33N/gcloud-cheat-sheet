# `roles/routeoptimization.viewer`

This role can view any long-running Operations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/routeoptimization.viewer` |
| Title | Route Optimization Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [routeoptimization](../overview.md) |

## Permissions

`roles/routeoptimization.viewer` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [routeoptimization](permissions/routeoptimization/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/routeoptimization.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
