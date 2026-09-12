# `roles/saasconfig.viewer`

Read access to SaaS Config resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/saasconfig.viewer` |
| Title | SaaS Config Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 3 |
| Service | [saasconfig](../overview.md) |

## Permissions

`roles/saasconfig.viewer` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [saasconfig](permissions/saasconfig/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/saasconfig.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
