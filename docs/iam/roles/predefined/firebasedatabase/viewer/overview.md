# `roles/firebasedatabase.viewer`

Read-only access to Firebase Realtime Database resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasedatabase.viewer` |
| Title | Firebase Realtime Database Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [firebasedatabase](../overview.md) |

## Permissions

`roles/firebasedatabase.viewer` grants 7 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebasedatabase](permissions/firebasedatabase/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasedatabase.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
