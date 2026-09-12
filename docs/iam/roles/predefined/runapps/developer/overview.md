# `roles/runapps.developer`

Access to create and change Serverless Integrations and their configuration.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/runapps.developer` |
| Title | Serverless Integrations Developer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 16 |
| Service | [runapps](../overview.md) |

## Permissions

`roles/runapps.developer` grants 16 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [runapps](permissions/runapps/overview.md) | 14 |

## Inspect this role live

```shell
gcloud iam roles describe roles/runapps.developer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
