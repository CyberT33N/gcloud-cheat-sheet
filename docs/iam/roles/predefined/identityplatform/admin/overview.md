# `roles/identityplatform.admin`

Full access to Identity Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/identityplatform.admin` |
| Title | Identity Platform Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 18 |
| Service | [identityplatform](../overview.md) |

## Permissions

`roles/identityplatform.admin` grants 18 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebaseauth](permissions/firebaseauth/overview.md) | 11 |
| [identitytoolkit](permissions/identitytoolkit/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/identityplatform.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
