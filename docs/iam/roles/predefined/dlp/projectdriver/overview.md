# `roles/dlp.projectdriver`

Permissions needed by the DLP service account to generate data profiles within a project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dlp.projectdriver` |
| Title | DLP Project Data Profiles Driver |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1676 |
| Service | [dlp](../overview.md) |

## Permissions

`roles/dlp.projectdriver` grants 1676 permissions across 69 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 189 |
| [alloydb](permissions/alloydb/overview.md) | 30 |
| [apigateway](permissions/apigateway/overview.md) | 8 |
| [apihub](permissions/apihub/overview.md) | 8 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 4 |
| [backupdr](permissions/backupdr/overview.md) | 8 |
| [beyondcorp](permissions/beyondcorp/overview.md) | 12 |
| [bigquery](permissions/bigquery/overview.md) | 72 |
| [bigquerymigration](permissions/bigquerymigration/overview.md) | 1 |
| [bigtable](permissions/bigtable/overview.md) | 8 |
| [certificatemanager](permissions/certificatemanager/overview.md) | 24 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [cloudasset](permissions/cloudasset/overview.md) | 563 |
| [clouddeploy](permissions/clouddeploy/overview.md) | 8 |
| [cloudkms](permissions/cloudkms/overview.md) | 9 |
| [cloudsql](permissions/cloudsql/overview.md) | 8 |
| [composer](permissions/composer/overview.md) | 4 |
| [compute](permissions/compute/overview.md) | 256 |
| [container](permissions/container/overview.md) | 4 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 3 |
| [datacatalog](permissions/datacatalog/overview.md) | 8 |
| [dataform](permissions/dataform/overview.md) | 9 |
| [datafusion](permissions/datafusion/overview.md) | 4 |
| [datamigration](permissions/datamigration/overview.md) | 12 |
| [dataplex](permissions/dataplex/overview.md) | 31 |
| [datastore](permissions/datastore/overview.md) | 4 |
| [datastream](permissions/datastream/overview.md) | 12 |
| [dlp](permissions/dlp/overview.md) | 63 |
| [dns](permissions/dns/overview.md) | 4 |
| [domains](permissions/domains/overview.md) | 4 |
| [eventarc](permissions/eventarc/overview.md) | 12 |
| [file](permissions/file/overview.md) | 12 |
| [financialservices](permissions/financialservices/overview.md) | 4 |
| [geminidataanalytics](permissions/geminidataanalytics/overview.md) | 1 |
| [gkemulticloud](permissions/gkemulticloud/overview.md) | 4 |
| [gkeonprem](permissions/gkeonprem/overview.md) | 16 |
| [iam](permissions/iam/overview.md) | 8 |
| [krmapihosting](permissions/krmapihosting/overview.md) | 4 |
| [livestream](permissions/livestream/overview.md) | 12 |
| [logging](permissions/logging/overview.md) | 4 |
| [looker](permissions/looker/overview.md) | 4 |
| [managedidentities](permissions/managedidentities/overview.md) | 4 |
| [memcache](permissions/memcache/overview.md) | 4 |
| [metastore](permissions/metastore/overview.md) | 8 |
| [monitoring](permissions/monitoring/overview.md) | 9 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 8 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 4 |
| [networksecurity](permissions/networksecurity/overview.md) | 12 |
| [networkservices](permissions/networkservices/overview.md) | 16 |
| [notebooks](permissions/notebooks/overview.md) | 4 |
| [parametermanager](permissions/parametermanager/overview.md) | 4 |
| [privateca](permissions/privateca/overview.md) | 8 |
| [pubsub](permissions/pubsub/overview.md) | 13 |
| [recaptchaenterprise](permissions/recaptchaenterprise/overview.md) | 4 |
| [recommender](permissions/recommender/overview.md) | 12 |
| [redis](permissions/redis/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 12 |
| [run](permissions/run/overview.md) | 8 |
| [secretmanager](permissions/secretmanager/overview.md) | 4 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [spanner](permissions/spanner/overview.md) | 4 |
| [storage](permissions/storage/overview.md) | 13 |
| [tpu](permissions/tpu/overview.md) | 4 |
| [transcoder](permissions/transcoder/overview.md) | 8 |
| [videostitcher](permissions/videostitcher/overview.md) | 16 |
| [vmmigration](permissions/vmmigration/overview.md) | 8 |
| [vmwareengine](permissions/vmwareengine/overview.md) | 20 |
| [workflows](permissions/workflows/overview.md) | 4 |
| [workstations](permissions/workstations/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dlp.projectdriver --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
