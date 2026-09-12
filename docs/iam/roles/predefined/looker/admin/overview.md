# `roles/looker.admin`

Full access to all Looker resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/looker.admin` |
| Title | Looker Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 26 |
| Service | [looker](../overview.md) |

## Permissions

`roles/looker.admin` grants 26 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [looker](permissions/looker/overview.md) | 22 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/looker.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
