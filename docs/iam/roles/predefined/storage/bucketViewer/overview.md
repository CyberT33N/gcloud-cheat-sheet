# `roles/storage.bucketViewer`

Grants permission to view buckets and their metadata, excluding IAM policies.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.bucketViewer` |
| Title | Storage Bucket Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 2 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.bucketViewer` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.bucketViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
