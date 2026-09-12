# `roles/storage.legacyBucketOwner`

Grants permission to create, replace, and delete objects; list objects in a bucket; create, delete, and list tag bindings; read object metadata when listing (excluding IAM policies); and read and edit bucket metadata, including IAM policies.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.legacyBucketOwner` |
| Title | Storage Legacy Bucket Owner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 47 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.legacyBucketOwner` grants 47 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [storage](permissions/storage/overview.md) | 47 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.legacyBucketOwner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
