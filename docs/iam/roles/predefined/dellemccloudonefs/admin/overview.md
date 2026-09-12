# `roles/dellemccloudonefs.admin`

This role is managed by Dell EMC, not Google.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dellemccloudonefs.admin` |
| Title | Dell EMC Cloud OneFS Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 13 |
| Service | [dellemccloudonefs](../overview.md) |

## Permissions

`roles/dellemccloudonefs.admin` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudonefs.isiloncloud.com](permissions/cloudonefs.isiloncloud.com/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dellemccloudonefs.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
