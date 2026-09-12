# `roles/cloudfunctions.viewer`

Read-only access to functions and locations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudfunctions.viewer` |
| Title | Cloud Functions Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 117 |
| Service | [cloudfunctions](../overview.md) |

## Permissions

`roles/cloudfunctions.viewer` grants 117 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 6 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 6 |
| [eventarc](permissions/eventarc/overview.md) | 39 |
| [recommender](permissions/recommender/overview.md) | 22 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [run](permissions/run/overview.md) | 30 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudfunctions.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
