# `roles/bigquerymigration.serviceAgent`

Access required for the BigQuery Migration Service to perform data discovery, metadata registration, and manage data transfers.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquerymigration.serviceAgent` |
| Title | BigQuery Migration Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [bigquerymigration](../overview.md) |

## Permissions

`roles/bigquerymigration.serviceAgent` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquerymigration.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
