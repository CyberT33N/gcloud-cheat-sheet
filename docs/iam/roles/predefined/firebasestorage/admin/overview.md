# `roles/firebasestorage.admin`

Full management of Cloud Storage for Firebase.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasestorage.admin` |
| Title | Cloud Storage for Firebase Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 12 |
| Service | [firebasestorage](../overview.md) |

## Permissions

`roles/firebasestorage.admin` grants 12 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebasestorage](permissions/firebasestorage/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasestorage.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
