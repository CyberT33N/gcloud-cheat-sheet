# `roles/privateca.admin`

Full access to all CA Service resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/privateca.admin` |
| Title | CA Service Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 60 |
| Service | [privateca](../overview.md) |

## Permissions

`roles/privateca.admin` grants 60 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [privateca](permissions/privateca/overview.md) | 57 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/privateca.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
