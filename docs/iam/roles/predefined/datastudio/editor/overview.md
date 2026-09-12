# `roles/datastudio.editor`

Editor of a Data Studio resource

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datastudio.editor` |
| Title | Data Studio Asset Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 10 |
| Service | [datastudio](../overview.md) |

## Permissions

`roles/datastudio.editor` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datastudio](permissions/datastudio/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datastudio.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
