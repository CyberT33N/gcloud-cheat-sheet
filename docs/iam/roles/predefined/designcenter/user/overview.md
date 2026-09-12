# `roles/designcenter.user`

Readonly access to Application Design Center resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/designcenter.user` |
| Title | Application Design Center User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 115 |
| Service | [designcenter](../overview.md) |

## Permissions

`roles/designcenter.user` grants 115 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apphub](permissions/apphub/overview.md) | 1 |
| [auditmanager](permissions/auditmanager/overview.md) | 15 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 31 |
| [container](permissions/container/overview.md) | 1 |
| [designcenter](permissions/designcenter/overview.md) | 39 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 24 |

## Inspect this role live

```shell
gcloud iam roles describe roles/designcenter.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
