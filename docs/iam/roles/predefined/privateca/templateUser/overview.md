# `roles/privateca.templateUser`

Read, list and use certificate templates.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/privateca.templateUser` |
| Title | CA Service Certificate Template User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [privateca](../overview.md) |

## Permissions

`roles/privateca.templateUser` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [privateca](permissions/privateca/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/privateca.templateUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
