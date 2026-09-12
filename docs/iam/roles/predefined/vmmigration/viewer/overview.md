# `roles/vmmigration.viewer`

Ability to view all VM Migration objects

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vmmigration.viewer` |
| Title | VM Migration Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 30 |
| Service | [vmmigration](../overview.md) |

## Permissions

`roles/vmmigration.viewer` grants 30 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [vmmigration](permissions/vmmigration/overview.md) | 28 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vmmigration.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
