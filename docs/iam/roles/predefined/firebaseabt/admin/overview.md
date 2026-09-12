# `roles/firebaseabt.admin`

Full read/write access to Firebase A/B Testing resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaseabt.admin` |
| Title | Firebase A/B Testing Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 12 |
| Service | [firebaseabt](../overview.md) |

## Permissions

`roles/firebaseabt.admin` grants 12 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebaseabt](permissions/firebaseabt/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaseabt.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
