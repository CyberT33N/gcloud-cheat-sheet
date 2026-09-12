# `roles/parametermanager.templateAccessor`

Grants read access to ParameterManager TemplateVersion resources. Intended for users & applications that need to perform read operations on TemplateVersions only.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/parametermanager.templateAccessor` |
| Title | Parameter Manager Template Accessor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 1 |
| Service | [parametermanager](../overview.md) |

## Permissions

`roles/parametermanager.templateAccessor` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [parametermanager](permissions/parametermanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/parametermanager.templateAccessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
