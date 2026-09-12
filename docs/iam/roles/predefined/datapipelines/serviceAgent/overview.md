# `roles/datapipelines.serviceAgent`

Gives Datapipelines service permissions to create Dataflow & Cloud Scheduler jobs in the user project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datapipelines.serviceAgent` |
| Title | Datapipelines Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 163 |
| Service | [datapipelines](../overview.md) |

## Permissions

`roles/datapipelines.serviceAgent` grants 163 permissions across 20 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [bigquery](permissions/bigquery/overview.md) | 1 |
| [bigtable](permissions/bigtable/overview.md) | 1 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 8 |
| [cloudscheduler](permissions/cloudscheduler/overview.md) | 11 |
| [compute](permissions/compute/overview.md) | 4 |
| [dataflow](permissions/dataflow/overview.md) | 11 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 3 |
| [monitoring](permissions/monitoring/overview.md) | 9 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 2 |
| [recommender](permissions/recommender/overview.md) | 15 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datapipelines.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
