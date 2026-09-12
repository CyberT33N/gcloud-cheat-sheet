# `roles/modelarmor.serviceAgent`

Gives Model Armor Service Account permission to make DLP calls.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/modelarmor.serviceAgent` |
| Title | Model Armor Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [modelarmor](../overview.md) |

## Permissions

`roles/modelarmor.serviceAgent` grants 17 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dlp](permissions/dlp/overview.md) | 16 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/modelarmor.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
