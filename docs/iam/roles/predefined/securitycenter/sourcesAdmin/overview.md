# `roles/securitycenter.sourcesAdmin`

Admin access to sources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.sourcesAdmin` |
| Title | Security Center Sources Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.sourcesAdmin` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [securitycenter](permissions/securitycenter/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.sourcesAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
