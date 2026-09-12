# `roles/storage.objectUser`

Access to create, read, update and delete objects and multipart uploads in GCS.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.objectUser` |
| Title | Storage Object User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 28 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.objectUser` grants 28 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 24 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.objectUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
