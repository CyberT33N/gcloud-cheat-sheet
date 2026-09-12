# `roles/parametermanager.admin`

Grants full access to all Parameter Manager resources. Intended for project admins & owners who need to perform all administrative tasks.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/parametermanager.admin` |
| Title | Parameter Manager Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 30 |
| Service | [parametermanager](../overview.md) |

## Permissions

`roles/parametermanager.admin` grants 30 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [parametermanager](permissions/parametermanager/overview.md) | 28 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/parametermanager.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
