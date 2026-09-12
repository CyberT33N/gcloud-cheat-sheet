# `roles/storage.objectCreator`

Allows users to create objects. Does not give permission to view, delete, or replace objects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/storage.objectCreator` |
| Title | Storage Object Creator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [storage](../overview.md) |

## Permissions

`roles/storage.objectCreator` grants 10 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/storage.objectCreator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
