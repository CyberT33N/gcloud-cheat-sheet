# `roles/privateca.caManager`

Create and manage CAs, revoke certificates, create certificates templates, and read-only access for CA Service resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/privateca.caManager` |
| Title | CA Service Operation Manager |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 47 |
| Service | [privateca](../overview.md) |

## Permissions

`roles/privateca.caManager` grants 47 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [privateca](permissions/privateca/overview.md) | 44 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/privateca.caManager --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
