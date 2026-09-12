# `roles/datalineage.producer`

Grants access to creating all resources in Data Lineage API

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datalineage.producer` |
| Title | Data Lineage Events Producer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [datalineage](../overview.md) |

## Permissions

`roles/datalineage.producer` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datalineage](permissions/datalineage/overview.md) | 10 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datalineage.producer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
