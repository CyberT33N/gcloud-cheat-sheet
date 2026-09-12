# `roles/dataprep.serviceAgent`

Dataprep service identity. Includes access to service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataprep.serviceAgent` |
| Title | Dataprep Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 560 |
| Service | [dataprep](../overview.md) |

## Permissions

`roles/dataprep.serviceAgent` grants 560 permissions across 15 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 60 |
| [bigquerymigration](permissions/bigquerymigration/overview.md) | 1 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 8 |
| [compute](permissions/compute/overview.md) | 412 |
| [dataflow](permissions/dataflow/overview.md) | 11 |
| [dataform](permissions/dataform/overview.md) | 5 |
| [dataplex](permissions/dataplex/overview.md) | 12 |
| [iam](permissions/iam/overview.md) | 3 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 3 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 30 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataprep.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
