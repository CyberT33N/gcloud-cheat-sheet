# `roles/dataform.editor`

Edit access to Workspaces and Read-only access to Repositories.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataform.editor` |
| Title | Dataform Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 62 |
| Service | [dataform](../overview.md) |

## Permissions

`roles/dataform.editor` grants 62 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataform](permissions/dataform/overview.md) | 60 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataform.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
