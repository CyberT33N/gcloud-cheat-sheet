# `roles/mapsadmin.admin`

Grants permission to read and write everything

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/mapsadmin.admin` |
| Title | Maps API Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [mapsadmin](../overview.md) |

## Permissions

`roles/mapsadmin.admin` grants 23 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [mapsadmin](permissions/mapsadmin/overview.md) | 21 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/mapsadmin.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
