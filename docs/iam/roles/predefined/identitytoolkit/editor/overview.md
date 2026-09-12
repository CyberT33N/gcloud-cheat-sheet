# `roles/identitytoolkit.editor`

Write access to Identity Toolkit resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/identitytoolkit.editor` |
| Title | Identity Toolkit editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 22 |
| Service | [identitytoolkit](../overview.md) |

## Permissions

`roles/identitytoolkit.editor` grants 22 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebaseauth](permissions/firebaseauth/overview.md) | 11 |
| [identitytoolkit](permissions/identitytoolkit/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/identitytoolkit.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
