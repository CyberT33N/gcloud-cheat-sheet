# `roles/firebaseapphosting.developer`

Grants read & update access to Firebase App Hosting backend, builds, and releases resources, plus permission to invoke the backend, but doesn't allow for new backends to be created.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaseapphosting.developer` |
| Title | Firebase App Hosting Developer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 25 |
| Service | [firebaseapphosting](../overview.md) |

## Permissions

`roles/firebaseapphosting.developer` grants 25 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebaseapphosting](permissions/firebaseapphosting/overview.md) | 23 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaseapphosting.developer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
