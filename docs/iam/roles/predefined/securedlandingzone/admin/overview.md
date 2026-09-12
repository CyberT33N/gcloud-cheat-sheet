# `roles/securedlandingzone.admin`

Admin role for Secured Landing Zone

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securedlandingzone.admin` |
| Title | Secured Landing Zone Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 10 |
| Service | [securedlandingzone](../overview.md) |

## Permissions

`roles/securedlandingzone.admin` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securedlandingzone](permissions/securedlandingzone/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securedlandingzone.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
