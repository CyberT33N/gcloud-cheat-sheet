# `roles/saasservicemgmt.serviceAgent`

Service Agent used by SaaS Service Management.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/saasservicemgmt.serviceAgent` |
| Title | SaaS Service Management Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 90 |
| Service | [saasservicemgmt](../overview.md) |

## Permissions

`roles/saasservicemgmt.serviceAgent` grants 90 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apphub](permissions/apphub/overview.md) | 9 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 4 |
| [config](permissions/config/overview.md) | 7 |
| [designcenter](permissions/designcenter/overview.md) | 5 |
| [monitoring](permissions/monitoring/overview.md) | 2 |
| [saasservicemgmt](permissions/saasservicemgmt/overview.md) | 54 |
| [storage](permissions/storage/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/saasservicemgmt.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
