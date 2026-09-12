# `roles/gkeonprem.viewer`

Read-only access to GKE on-prem all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkeonprem.viewer` |
| Title | GKE on-prem Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 37 |
| Service | [gkeonprem](../overview.md) |

## Permissions

`roles/gkeonprem.viewer` grants 37 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkeonprem](permissions/gkeonprem/overview.md) | 35 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkeonprem.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
