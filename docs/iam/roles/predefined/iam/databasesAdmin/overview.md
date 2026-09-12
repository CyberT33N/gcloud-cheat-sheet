# `roles/iam.databasesAdmin`

Role for an administrator to manage all structured and non structured datastores in GCP.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.databasesAdmin` |
| Title | Databases Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1487 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.databasesAdmin` grants 1487 permissions across 36 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [alloydb](permissions/alloydb/overview.md) | 52 |
| [appengine](permissions/appengine/overview.md) | 1 |
| [backupdr](permissions/backupdr/overview.md) | 30 |
| [biglake](permissions/biglake/overview.md) | 38 |
| [bigquery](permissions/bigquery/overview.md) | 130 |
| [bigquerymigration](permissions/bigquerymigration/overview.md) | 1 |
| [bigtable](permissions/bigtable/overview.md) | 90 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 6 |
| [cloudkms](permissions/cloudkms/overview.md) | 28 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [cloudsql](permissions/cloudsql/overview.md) | 72 |
| [compute](permissions/compute/overview.md) | 412 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 8 |
| [dataflow](permissions/dataflow/overview.md) | 6 |
| [dataform](permissions/dataform/overview.md) | 98 |
| [dataplex](permissions/dataplex/overview.md) | 13 |
| [datastore](permissions/datastore/overview.md) | 28 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 7 |
| [logging](permissions/logging/overview.md) | 26 |
| [memcache](permissions/memcache/overview.md) | 20 |
| [memorystore](permissions/memorystore/overview.md) | 21 |
| [monitoring](permissions/monitoring/overview.md) | 61 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 1 |
| [observability](permissions/observability/overview.md) | 1 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 17 |
| [recommender](permissions/recommender/overview.md) | 83 |
| [redis](permissions/redis/overview.md) | 48 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 4 |
| [serviceusage](permissions/serviceusage/overview.md) | 13 |
| [spanner](permissions/spanner/overview.md) | 84 |
| [stackdriver](permissions/stackdriver/overview.md) | 4 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.databasesAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
