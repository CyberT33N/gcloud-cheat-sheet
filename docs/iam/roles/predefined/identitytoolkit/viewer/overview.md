# `roles/identitytoolkit.viewer`

Read access to Identity Toolkit resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/identitytoolkit.viewer` |
| Title | Identity Toolkit Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [identitytoolkit](../overview.md) |

## Permissions

`roles/identitytoolkit.viewer` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebaseauth](permissions/firebaseauth/overview.md) | 2 |
| [identitytoolkit](permissions/identitytoolkit/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/identitytoolkit.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
