# `roles/firebaseml.admin`

Full read/write access to Firebase ML Kit resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaseml.admin` |
| Title | Firebase ML Kit Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 14 |
| Service | [firebaseml](../overview.md) |

## Permissions

`roles/firebaseml.admin` grants 14 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebaseml](permissions/firebaseml/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaseml.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
