# `roles/developerconnect.serviceAgent`

Gives the Developer Connect API Service Account access to necessary GCP resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/developerconnect.serviceAgent` |
| Title | Developer Connect Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [developerconnect](../overview.md) |

## Permissions

`roles/developerconnect.serviceAgent` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apphub](permissions/apphub/overview.md) | 5 |
| [developerconnect](permissions/developerconnect/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/developerconnect.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
