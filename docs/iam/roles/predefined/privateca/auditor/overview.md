# `roles/privateca.auditor`

Read-only access to all CA Service resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/privateca.auditor` |
| Title | CA Service Auditor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 24 |
| Service | [privateca](../overview.md) |

## Permissions

`roles/privateca.auditor` grants 24 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [privateca](permissions/privateca/overview.md) | 22 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/privateca.auditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
