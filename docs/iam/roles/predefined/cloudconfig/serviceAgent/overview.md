# `roles/cloudconfig.serviceAgent`

Gives Infrastructure Manager service agent access to managed resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudconfig.serviceAgent` |
| Title | Infrastructure Manager Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [cloudconfig](../overview.md) |

## Permissions

`roles/cloudconfig.serviceAgent` grants 20 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 5 |
| [iam](permissions/iam/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudconfig.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
