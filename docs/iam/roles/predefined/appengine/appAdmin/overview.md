# `roles/appengine.appAdmin`

Full management of App Engine apps (but not storage).

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/appengine.appAdmin` |
| Title | App Engine Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 38 |
| Service | [appengine](../overview.md) |

## Permissions

`roles/appengine.appAdmin` grants 38 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 24 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 4 |
| [recommender](permissions/recommender/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/appengine.appAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
