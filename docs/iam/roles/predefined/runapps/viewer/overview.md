# `roles/runapps.viewer`

Readonly access to Serverless Integrations resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/runapps.viewer` |
| Title | Serverless Integrations Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 11 |
| Service | [runapps](../overview.md) |

## Permissions

`roles/runapps.viewer` grants 11 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [runapps](permissions/runapps/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/runapps.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
