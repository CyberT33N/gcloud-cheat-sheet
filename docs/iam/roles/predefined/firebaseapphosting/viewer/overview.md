# `roles/firebaseapphosting.viewer`

Grants readonly access to Firebase App Hosting resources, but not permission to invoke the backend.  Intended for auditors, PMs, ect.  Includes minimal viewer permissions for Firebase Console.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaseapphosting.viewer` |
| Title | Firebase App Hosting Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [firebaseapphosting](../overview.md) |

## Permissions

`roles/firebaseapphosting.viewer` grants 15 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebaseapphosting](permissions/firebaseapphosting/overview.md) | 13 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaseapphosting.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
