# `roles/modelarmor.user`

Grants access to sanitize APIs for templates and to use and test topics. Intended for users & applications which plan to use a template or topic for sanitization.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/modelarmor.user` |
| Title | Model Armor User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [modelarmor](../overview.md) |

## Permissions

`roles/modelarmor.user` grants 11 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [modelarmor](permissions/modelarmor/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/modelarmor.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
