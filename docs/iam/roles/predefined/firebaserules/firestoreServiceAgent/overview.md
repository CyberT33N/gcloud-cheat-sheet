# `roles/firebaserules.firestoreServiceAgent`

Grants Firebase Security Rules access to Firestore for providing cross-service Rules.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaserules.firestoreServiceAgent` |
| Title | Firebase Rules Firestore Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [firebaserules](../overview.md) |

## Permissions

`roles/firebaserules.firestoreServiceAgent` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datastore](permissions/datastore/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaserules.firestoreServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
