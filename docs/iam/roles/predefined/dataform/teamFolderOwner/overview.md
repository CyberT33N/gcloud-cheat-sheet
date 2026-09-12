# `roles/dataform.teamFolderOwner`

Full access to a team folder and its contents. Can share the team folder and its contents.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataform.teamFolderOwner` |
| Title | Team Folder Owner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 77 |
| Service | [dataform](../overview.md) |

## Permissions

`roles/dataform.teamFolderOwner` grants 77 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataform](permissions/dataform/overview.md) | 75 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataform.teamFolderOwner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
