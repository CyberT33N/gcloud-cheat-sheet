# `roles/datastream.serviceAgent`

Grants Cloud Datastream permissions to write data in the user project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datastream.serviceAgent` |
| Title | Datastream Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 51 |
| Service | [datastream](../overview.md) |

## Permissions

`roles/datastream.serviceAgent` grants 51 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 17 |
| [compute](permissions/compute/overview.md) | 17 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [spanner](permissions/spanner/overview.md) | 11 |
| [storage](permissions/storage/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datastream.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
