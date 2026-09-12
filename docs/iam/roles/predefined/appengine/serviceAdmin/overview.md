# `roles/appengine.serviceAdmin`

Can view and change traffic splits, scaling settings, and delete old versions; can't create new versions.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/appengine.serviceAdmin` |
| Title | App Engine Service Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 26 |
| Service | [appengine](../overview.md) |

## Permissions

`roles/appengine.serviceAdmin` grants 26 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 15 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/appengine.serviceAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
