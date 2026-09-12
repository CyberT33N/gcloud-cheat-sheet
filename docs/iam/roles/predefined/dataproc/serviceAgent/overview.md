# `roles/dataproc.serviceAgent`

Gives Dataproc Service Account access to service accounts, compute resources, storage resources, and kubernetes resources. Includes access to service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataproc.serviceAgent` |
| Title | Dataproc Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 497 |
| Service | [dataproc](../overview.md) |

## Permissions

`roles/dataproc.serviceAgent` grants 497 permissions across 18 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [biglake](permissions/biglake/overview.md) | 1 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 255 |
| [container](permissions/container/overview.md) | 33 |
| [dataproc](permissions/dataproc/overview.md) | 38 |
| [dataprocrm](permissions/dataprocrm/overview.md) | 19 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 2 |
| [metastore](permissions/metastore/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 9 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 11 |
| [serviceusage](permissions/serviceusage/overview.md) | 11 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataproc.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
