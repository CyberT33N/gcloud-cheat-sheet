# `roles/biglake.metadataViewer`

Provides read-only metadata access to all BigLake resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/biglake.metadataViewer` |
| Title | BigLake Metadata Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 12 |
| Service | [biglake](../overview.md) |

## Permissions

`roles/biglake.metadataViewer` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [biglake](permissions/biglake/overview.md) | 10 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/biglake.metadataViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
