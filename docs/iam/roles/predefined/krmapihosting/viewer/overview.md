# `roles/krmapihosting.viewer`

Read-only access to all Config Controller resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/krmapihosting.viewer` |
| Title | Config Controller Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [krmapihosting](../overview.md) |

## Permissions

`roles/krmapihosting.viewer` grants 11 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [krmapihosting](permissions/krmapihosting/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/krmapihosting.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
