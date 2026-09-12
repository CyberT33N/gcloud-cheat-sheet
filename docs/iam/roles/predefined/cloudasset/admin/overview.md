# `roles/cloudasset.admin`

Admin role for cloudasset

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudasset.admin` |
| Title | Cloud Asset Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 582 |
| Service | [cloudasset](../overview.md) |

## Permissions

`roles/cloudasset.admin` grants 582 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 576 |
| [recommender](permissions/recommender/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudasset.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
