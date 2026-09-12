# `roles/automlrecommendations.viewer`

Viewer of all Recommendations AI resources except automlrecommendations.apiKeys. To have all read access use Recommendations AI Admin Viewer role instead.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/automlrecommendations.viewer` |
| Title | Recommendations AI Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 31 |
| Service | [automlrecommendations](../overview.md) |

## Permissions

`roles/automlrecommendations.viewer` grants 31 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automlrecommendations](permissions/automlrecommendations/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [retail](permissions/retail/overview.md) | 9 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/automlrecommendations.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
