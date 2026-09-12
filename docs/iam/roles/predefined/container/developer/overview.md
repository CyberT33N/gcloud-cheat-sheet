# `roles/container.developer`

Full access to Kubernetes API objects inside Kubernetes Clusters.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/container.developer` |
| Title | Kubernetes Engine Developer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 386 |
| Service | [container](../overview.md) |

## Permissions

`roles/container.developer` grants 386 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [container](permissions/container/overview.md) | 370 |
| [recommender](permissions/recommender/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/container.developer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
