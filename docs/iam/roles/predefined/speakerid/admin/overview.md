# `roles/speakerid.admin`

Grants full access to all Speaker ID resources, including project settings.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/speakerid.admin` |
| Title | Speaker ID Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [speakerid](../overview.md) |

## Permissions

`roles/speakerid.admin` grants 11 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [speakerid](permissions/speakerid/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/speakerid.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
