# `roles/firebasedatabase.admin`

Full read/write access to Firebase Realtime Database resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasedatabase.admin` |
| Title | Firebase Realtime Database Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [firebasedatabase](../overview.md) |

## Permissions

`roles/firebasedatabase.admin` grants 13 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebasedatabase](permissions/firebasedatabase/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasedatabase.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
