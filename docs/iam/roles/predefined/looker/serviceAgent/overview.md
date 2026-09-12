# `roles/looker.serviceAgent`

Gives the Looker service account permission to manage customer resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/looker.serviceAgent` |
| Title | Looker Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 18 |
| Service | [looker](../overview.md) |

## Permissions

`roles/looker.serviceAgent` grants 18 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 13 |
| [compute](permissions/compute/overview.md) | 1 |
| [looker](permissions/looker/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/looker.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
