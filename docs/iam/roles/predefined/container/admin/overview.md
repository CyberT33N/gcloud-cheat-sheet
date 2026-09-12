# `roles/container.admin`

Full management of Kubernetes Clusters and their Kubernetes API objects.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/container.admin` |
| Title | Kubernetes Engine Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 434 |
| Service | [container](../overview.md) |

## Permissions

`roles/container.admin` grants 434 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [container](permissions/container/overview.md) | 413 |
| [recommender](permissions/recommender/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/container.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
