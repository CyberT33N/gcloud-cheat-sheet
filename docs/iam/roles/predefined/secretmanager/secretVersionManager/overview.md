# `roles/secretmanager.secretVersionManager`

Allows creating and managing versions of existing secrets.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/secretmanager.secretVersionManager` |
| Title | Secret Manager Secret Version Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [secretmanager](../overview.md) |

## Permissions

`roles/secretmanager.secretVersionManager` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [secretmanager](permissions/secretmanager/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/secretmanager.secretVersionManager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
