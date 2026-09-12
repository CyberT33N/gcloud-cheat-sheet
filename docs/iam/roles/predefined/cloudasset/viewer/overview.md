# `roles/cloudasset.viewer`

Read only access to cloud assets metadata

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudasset.viewer` |
| Title | Cloud Asset Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 567 |
| Service | [cloudasset](../overview.md) |

## Permissions

`roles/cloudasset.viewer` grants 567 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 563 |
| [recommender](permissions/recommender/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudasset.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
