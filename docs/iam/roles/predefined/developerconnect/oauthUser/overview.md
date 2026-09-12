# `roles/developerconnect.oauthUser`

Grants read and write access to User resources, and read access to AccountConnectors.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/developerconnect.oauthUser` |
| Title | Developer Connect OAuth User |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 18 |
| Service | [developerconnect](../overview.md) |

## Permissions

`roles/developerconnect.oauthUser` grants 18 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [developerconnect](permissions/developerconnect/overview.md) | 16 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/developerconnect.oauthUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
