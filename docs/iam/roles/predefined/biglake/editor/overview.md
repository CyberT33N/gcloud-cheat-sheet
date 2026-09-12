# `roles/biglake.editor`

Provides read and write access to all BigLake resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/biglake.editor` |
| Title | BigLake Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 26 |
| Service | [biglake](../overview.md) |

## Permissions

`roles/biglake.editor` grants 26 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [biglake](permissions/biglake/overview.md) | 24 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/biglake.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
