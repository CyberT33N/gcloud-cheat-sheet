# `roles/businessaicode.user`

A user who can use Business AI Code API

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/businessaicode.user` |
| Title | User role for Business AI Code API |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [businessaicode](../overview.md) |

## Permissions

`roles/businessaicode.user` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [businessaicode](permissions/businessaicode/overview.md) | 5 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/businessaicode.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
