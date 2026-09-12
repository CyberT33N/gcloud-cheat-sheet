# `roles/firebasehosting.admin`

Full read/write access to Firebase Hosting resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasehosting.admin` |
| Title | Firebase Hosting Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [firebasehosting](../overview.md) |

## Permissions

`roles/firebasehosting.admin` grants 10 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebasehosting](permissions/firebasehosting/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasehosting.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
