# `roles/cloudasset.owner`

Full access to cloud assets metadata

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudasset.owner` |
| Title | Cloud Asset Owner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 581 |
| Service | [cloudasset](../overview.md) |

## Permissions

`roles/cloudasset.owner` grants 581 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 576 |
| [recommender](permissions/recommender/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudasset.owner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
