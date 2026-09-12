# `roles/firebaseauth.editor`

Write access to Firebase Authentication resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaseauth.editor` |
| Title | Firebase Authentication editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [firebaseauth](../overview.md) |

## Permissions

`roles/firebaseauth.editor` grants 16 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebaseauth](permissions/firebaseauth/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaseauth.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
