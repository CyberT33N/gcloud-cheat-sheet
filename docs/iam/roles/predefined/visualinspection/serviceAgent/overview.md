# `roles/visualinspection.serviceAgent`

Grants Visual Inspection AI Service Agent admin roles for accessing/exporting training data, pushing containers artifacts to GCR and ArtifactsRegistry, and Vertex AI for storing data and running training jobs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/visualinspection.serviceAgent` |
| Title | Visual Inspection AI Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 647 |
| Service | [visualinspection](../overview.md) |

## Permissions

`roles/visualinspection.serviceAgent` grants 647 permissions across 11 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 478 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 61 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 9 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/visualinspection.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
