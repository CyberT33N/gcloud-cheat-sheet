# `roles/composer.serviceAgent`

Cloud Composer API service agent can manage environments.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/composer.serviceAgent` |
| Title | Cloud Composer API Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2104 |
| Service | [composer](../overview.md) |

## Permissions

`roles/composer.serviceAgent` grants 2104 permissions across 33 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 24 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 9 |
| [backupdr](permissions/backupdr/overview.md) | 33 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 6 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [cloudsql](permissions/cloudsql/overview.md) | 72 |
| [composer](permissions/composer/overview.md) | 2 |
| [compute](permissions/compute/overview.md) | 867 |
| [container](permissions/container/overview.md) | 413 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 8 |
| [deploymentmanager](permissions/deploymentmanager/overview.md) | 30 |
| [dns](permissions/dns/overview.md) | 3 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 5 |
| [logging](permissions/logging/overview.md) | 59 |
| [monitoring](permissions/monitoring/overview.md) | 31 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 39 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 2 |
| [networksecurity](permissions/networksecurity/overview.md) | 125 |
| [networkservices](permissions/networkservices/overview.md) | 132 |
| [observability](permissions/observability/overview.md) | 1 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 45 |
| [recommender](permissions/recommender/overview.md) | 83 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 4 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 10 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/composer.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
