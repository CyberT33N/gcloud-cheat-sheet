# `roles/gameservices.serviceAgent`

Gives Game Services Service Account access to GCP resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gameservices.serviceAgent` |
| Title | Game Services Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 432 |
| Service | [gameservices](../overview.md) |

## Permissions

`roles/gameservices.serviceAgent` grants 432 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [container](permissions/container/overview.md) | 391 |
| [gkehub](permissions/gkehub/overview.md) | 24 |
| [iam](permissions/iam/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gameservices.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
