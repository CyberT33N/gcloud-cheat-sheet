# `roles/gkebackup.serviceAgent`

Grants the Backup for GKE Service Account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkebackup.serviceAgent` |
| Title | Backup for GKE Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 403 |
| Service | [gkebackup](../overview.md) |

## Permissions

`roles/gkebackup.serviceAgent` grants 403 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 12 |
| [container](permissions/container/overview.md) | 373 |
| [gkebackup](permissions/gkebackup/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkebackup.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
