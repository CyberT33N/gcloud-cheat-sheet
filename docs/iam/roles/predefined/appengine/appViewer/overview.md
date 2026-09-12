# `roles/appengine.appViewer`

Ability to view App Engine app status.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/appengine.appViewer` |
| Title | App Engine Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [appengine](../overview.md) |

## Permissions

`roles/appengine.appViewer` grants 19 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 10 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/appengine.appViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
