# `roles/run.sourceViewer`

View Cloud Run source deployed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/run.sourceViewer` |
| Title | Cloud Run Source Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 131 |
| Service | [run](../overview.md) |

## Permissions

`roles/run.sourceViewer` grants 131 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 2 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 6 |
| [eventarc](permissions/eventarc/overview.md) | 39 |
| [pubsub](permissions/pubsub/overview.md) | 17 |
| [recommender](permissions/recommender/overview.md) | 18 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 30 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/run.sourceViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
