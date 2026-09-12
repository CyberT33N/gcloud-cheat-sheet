# `roles/gkehub.editor`

Edit access to Fleet resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkehub.editor` |
| Title | Fleet Editor (formerly GKE Hub Editor) |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 55 |
| Service | [gkehub](../overview.md) |

## Permissions

`roles/gkehub.editor` grants 55 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 53 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkehub.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
