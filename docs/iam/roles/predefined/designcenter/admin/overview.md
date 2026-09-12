# `roles/designcenter.admin`

Full access to Application Design Center resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/designcenter.admin` |
| Title | Application Design Center Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 190 |
| Service | [designcenter](../overview.md) |

## Permissions

`roles/designcenter.admin` grants 190 permissions across 12 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apphub](permissions/apphub/overview.md) | 10 |
| [auditmanager](permissions/auditmanager/overview.md) | 15 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 2 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 31 |
| [config](permissions/config/overview.md) | 21 |
| [container](permissions/container/overview.md) | 1 |
| [designcenter](permissions/designcenter/overview.md) | 58 |
| [developerconnect](permissions/developerconnect/overview.md) | 24 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 24 |

## Inspect this role live

```shell
gcloud iam roles describe roles/designcenter.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
