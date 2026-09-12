# `roles/config.editor`

Edit access to Cloud Infrastructure Manager resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/config.editor` |
| Title | Cloud Infrastructure Manager Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 34 |
| Service | [config](../overview.md) |

## Permissions

`roles/config.editor` grants 34 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [config](permissions/config/overview.md) | 32 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/config.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
