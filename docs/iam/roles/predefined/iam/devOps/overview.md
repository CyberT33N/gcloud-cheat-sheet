# `roles/iam.devOps`

Enables DevOps users to build and deploy applications, create, manage and perform administrative tasks on associated GCP resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.devOps` |
| Title | Dev Ops |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 717 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.devOps` grants 717 permissions across 29 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apptopology](permissions/apptopology/overview.md) | 14 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 43 |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 15 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 31 |
| [clouddeploy](permissions/clouddeploy/overview.md) | 31 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 13 |
| [cloudkms](permissions/cloudkms/overview.md) | 9 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [cloudsql](permissions/cloudsql/overview.md) | 45 |
| [compute](permissions/compute/overview.md) | 24 |
| [developerconnect](permissions/developerconnect/overview.md) | 24 |
| [eventarc](permissions/eventarc/overview.md) | 67 |
| [iam](permissions/iam/overview.md) | 18 |
| [logging](permissions/logging/overview.md) | 77 |
| [monitoring](permissions/monitoring/overview.md) | 61 |
| [observability](permissions/observability/overview.md) | 1 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 43 |
| [recommender](permissions/recommender/overview.md) | 77 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 61 |
| [serviceusage](permissions/serviceusage/overview.md) | 12 |
| [source](permissions/source/overview.md) | 10 |
| [stackdriver](permissions/stackdriver/overview.md) | 4 |
| [storage](permissions/storage/overview.md) | 28 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.devOps --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
