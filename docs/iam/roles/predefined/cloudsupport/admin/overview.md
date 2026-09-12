# `roles/cloudsupport.admin`

Allows management of a support account without giving access to support cases.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsupport.admin` |
| Title | Support Account Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [cloudsupport](../overview.md) |

## Permissions

`roles/cloudsupport.admin` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudsupport](permissions/cloudsupport/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsupport.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
