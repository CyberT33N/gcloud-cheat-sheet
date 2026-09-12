# `roles/developerconnect.user`

Grants access to view the connection and to the features that interact with the actual repository such as reading content from the repository

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/developerconnect.user` |
| Title | Developer Connect User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [developerconnect](../overview.md) |

## Permissions

`roles/developerconnect.user` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [developerconnect](permissions/developerconnect/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/developerconnect.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
