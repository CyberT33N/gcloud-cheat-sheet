# `roles/automlrecommendations.adminViewer`

Viewer of all Recommendations AI resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/automlrecommendations.adminViewer` |
| Title | Recommendations AI Admin Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 32 |
| Service | [automlrecommendations](../overview.md) |

## Permissions

`roles/automlrecommendations.adminViewer` grants 32 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automlrecommendations](permissions/automlrecommendations/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [retail](permissions/retail/overview.md) | 9 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/automlrecommendations.adminViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
