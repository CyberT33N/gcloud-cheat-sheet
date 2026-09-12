# `roles/storage.legacyBucketReader`

Grants permission to list a bucket's contents and read bucket metadata, excluding IAM policies. Also grants permission to read object metadata when listing objects (excluding IAM policies).

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.legacyBucketReader` |
| Title | Storage Legacy Bucket Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.legacyBucketReader` grants 7 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [storage](permissions/storage/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.legacyBucketReader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
