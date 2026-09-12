# `roles/cloudaicompanion.serviceAgent`

Gives Gemini for Google Cloud components the proper permissions to function.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudaicompanion.serviceAgent` |
| Title | Gemini for Google Cloud Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 29 |
| Service | [cloudaicompanion](../overview.md) |

## Permissions

`roles/cloudaicompanion.serviceAgent` grants 29 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 9 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 5 |
| [developerconnect](permissions/developerconnect/overview.md) | 6 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudaicompanion.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
