# `roles/dataflow.serviceAgent`

Gives Cloud Dataflow service account access to managed resources. Includes access to service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataflow.serviceAgent` |
| Title | Cloud Dataflow Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1732 |
| Service | [dataflow](../overview.md) |

## Permissions

`roles/dataflow.serviceAgent` grants 1732 permissions across 32 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [bigquery](permissions/bigquery/overview.md) | 130 |
| [bigquerymigration](permissions/bigquerymigration/overview.md) | 1 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [clouddebugger](permissions/clouddebugger/overview.md) | 4 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 872 |
| [dataflow](permissions/dataflow/overview.md) | 11 |
| [dataform](permissions/dataform/overview.md) | 98 |
| [dataplex](permissions/dataplex/overview.md) | 13 |
| [dns](permissions/dns/overview.md) | 1 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 7 |
| [logging](permissions/logging/overview.md) | 59 |
| [monitoring](permissions/monitoring/overview.md) | 34 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 39 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 2 |
| [networksecurity](permissions/networksecurity/overview.md) | 125 |
| [networkservices](permissions/networkservices/overview.md) | 132 |
| [observability](permissions/observability/overview.md) | 1 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 51 |
| [recommender](permissions/recommender/overview.md) | 15 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 10 |
| [serviceusage](permissions/serviceusage/overview.md) | 11 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataflow.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
