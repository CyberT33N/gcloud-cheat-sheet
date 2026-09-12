# `roles/cloudfunctions.developer`

Read and write access to all functions-related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudfunctions.developer` |
| Title | Cloud Functions Developer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 225 |
| Service | [cloudfunctions](../overview.md) |

## Permissions

`roles/cloudfunctions.developer` grants 225 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 32 |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 6 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 13 |
| [eventarc](permissions/eventarc/overview.md) | 67 |
| [recommender](permissions/recommender/overview.md) | 32 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 61 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudfunctions.developer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
