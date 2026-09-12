# `roles/servicedirectory.admin`

Full control of all Service Directory resources and permissions.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/servicedirectory.admin` |
| Title | Service Directory Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 29 |
| Service | [servicedirectory](../overview.md) |

## Permissions

`roles/servicedirectory.admin` grants 29 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 27 |

## Inspect this role live

```shell
gcloud iam roles describe roles/servicedirectory.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
