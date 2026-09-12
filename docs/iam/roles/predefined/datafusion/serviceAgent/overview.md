# `roles/datafusion.serviceAgent`

Gives Cloud Data Fusion service account access to Service Networking, Cloud Dataproc, Cloud Storage, BigQuery, Cloud Spanner, and Cloud Bigtable resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datafusion.serviceAgent` |
| Title | Cloud Data Fusion API Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 743 |
| Service | [datafusion](../overview.md) |

## Permissions

`roles/datafusion.serviceAgent` grants 743 permissions across 27 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 74 |
| [bigtable](permissions/bigtable/overview.md) | 90 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 242 |
| [dataform](permissions/dataform/overview.md) | 5 |
| [dataplex](permissions/dataplex/overview.md) | 12 |
| [dataproc](permissions/dataproc/overview.md) | 55 |
| [dataprocrm](permissions/dataprocrm/overview.md) | 17 |
| [dns](permissions/dns/overview.md) | 6 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [geminidataanalytics](permissions/geminidataanalytics/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 11 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 8 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 2 |
| [networksecurity](permissions/networksecurity/overview.md) | 34 |
| [networkservices](permissions/networkservices/overview.md) | 44 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [spanner](permissions/spanner/overview.md) | 29 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datafusion.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
