# `roles/vectorsearch.viewer`

Grants read access to all vectorsearch resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vectorsearch.viewer` |
| Title | Vector Search Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [vectorsearch](../overview.md) |

## Permissions

`roles/vectorsearch.viewer` grants 14 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [vectorsearch](permissions/vectorsearch/overview.md) | 12 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vectorsearch.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
