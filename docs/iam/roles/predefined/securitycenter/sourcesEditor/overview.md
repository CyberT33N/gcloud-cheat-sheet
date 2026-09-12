# `roles/securitycenter.sourcesEditor`

Read-write access to sources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.sourcesEditor` |
| Title | Security Center Sources Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.sourcesEditor` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [securitycenter](permissions/securitycenter/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.sourcesEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
