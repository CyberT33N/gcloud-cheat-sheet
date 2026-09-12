# `roles/serviceextensions.editor`

Grants access to edit Service Extensions resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/serviceextensions.editor` |
| Title | Service Extensions Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 5 |
| Service | [serviceextensions](../overview.md) |

## Permissions

`roles/serviceextensions.editor` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceextensions](permissions/serviceextensions/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/serviceextensions.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
