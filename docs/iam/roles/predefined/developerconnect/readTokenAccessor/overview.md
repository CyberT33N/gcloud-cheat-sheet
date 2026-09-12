# `roles/developerconnect.readTokenAccessor`

Grants access to Read-Only tokens (both PAT and short-lived). Also grants access to view the git repository link.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/developerconnect.readTokenAccessor` |
| Title | Developer Connect Read Token Accessor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 3 |
| Service | [developerconnect](../overview.md) |

## Permissions

`roles/developerconnect.readTokenAccessor` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [developerconnect](permissions/developerconnect/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/developerconnect.readTokenAccessor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
