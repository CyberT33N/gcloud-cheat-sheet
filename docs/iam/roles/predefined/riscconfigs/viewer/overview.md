# `roles/riscconfigs.viewer`

Read-only access to RISC config resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/riscconfigs.viewer` |
| Title | RISC Configuration Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 2 |
| Service | [riscconfigs](../overview.md) |

## Permissions

`roles/riscconfigs.viewer` grants 2 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [clientauthconfig](permissions/clientauthconfig/overview.md) | 1 |
| [riscconfigurationservice](permissions/riscconfigurationservice/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/riscconfigs.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
