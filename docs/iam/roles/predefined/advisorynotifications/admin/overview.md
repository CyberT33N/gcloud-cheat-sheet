# `roles/advisorynotifications.admin`

Grants write access to settings in Advisory Notifications

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/advisorynotifications.admin` |
| Title | Advisory Notifications Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 6 |
| Service | [advisorynotifications](../overview.md) |

## Permissions

`roles/advisorynotifications.admin` grants 6 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [advisorynotifications](permissions/advisorynotifications/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/advisorynotifications.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
