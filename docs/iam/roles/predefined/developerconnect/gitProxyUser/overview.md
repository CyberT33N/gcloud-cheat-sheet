# `roles/developerconnect.gitProxyUser`

Grants read and write access to repositories through the Git Proxy.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/developerconnect.gitProxyUser` |
| Title | Developer Connect Git Proxy User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [developerconnect](../overview.md) |

## Permissions

`roles/developerconnect.gitProxyUser` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [developerconnect](permissions/developerconnect/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/developerconnect.gitProxyUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
