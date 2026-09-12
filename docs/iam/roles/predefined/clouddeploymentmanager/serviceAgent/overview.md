# `roles/clouddeploymentmanager.serviceAgent`

Allows Deployment Manager service to actuate resources across DM projects and folders

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/clouddeploymentmanager.serviceAgent` |
| Title | Cloud Deployment Manager Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 670 |
| Service | [clouddeploymentmanager](../overview.md) |

## Permissions

`roles/clouddeploymentmanager.serviceAgent` grants 670 permissions across 38 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [accesscontextmanager](permissions/accesscontextmanager/overview.md) | 9 |
| [appengine](permissions/appengine/overview.md) | 7 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 4 |
| [bigquery](permissions/bigquery/overview.md) | 17 |
| [bigtable](permissions/bigtable/overview.md) | 8 |
| [billing](permissions/billing/overview.md) | 2 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 2 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 8 |
| [cloudprivatecatalog](permissions/cloudprivatecatalog/overview.md) | 1 |
| [cloudscheduler](permissions/cloudscheduler/overview.md) | 4 |
| [cloudsql](permissions/cloudsql/overview.md) | 17 |
| [cloudtasks](permissions/cloudtasks/overview.md) | 3 |
| [compute](permissions/compute/overview.md) | 292 |
| [container](permissions/container/overview.md) | 100 |
| [datacatalog](permissions/datacatalog/overview.md) | 1 |
| [dataproc](permissions/dataproc/overview.md) | 12 |
| [deploymentmanager](permissions/deploymentmanager/overview.md) | 10 |
| [dns](permissions/dns/overview.md) | 16 |
| [file](permissions/file/overview.md) | 5 |
| [firebase](permissions/firebase/overview.md) | 2 |
| [firebaseanalytics](permissions/firebaseanalytics/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 13 |
| [logging](permissions/logging/overview.md) | 15 |
| [monitoring](permissions/monitoring/overview.md) | 24 |
| [networksecurity](permissions/networksecurity/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 12 |
| [redis](permissions/redis/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 22 |
| [runtimeconfig](permissions/runtimeconfig/overview.md) | 14 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 5 |
| [source](permissions/source/overview.md) | 1 |
| [spanner](permissions/spanner/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 11 |
| [vpcaccess](permissions/vpcaccess/overview.md) | 3 |
| [workflows](permissions/workflows/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/clouddeploymentmanager.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
