# `roles/anthos.serviceAgent`

Gives the Anthos service agent access to Cloud Platformresources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/anthos.serviceAgent` |
| Title | Anthos Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [anthos](../overview.md) |

## Permissions

`roles/anthos.serviceAgent` grants 14 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 5 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/anthos.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
