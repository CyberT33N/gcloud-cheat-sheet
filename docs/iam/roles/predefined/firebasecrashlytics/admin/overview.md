# `roles/firebasecrashlytics.admin`

Full read/write access to Firebase Crashlytics resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasecrashlytics.admin` |
| Title | Firebase Crashlytics Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [firebasecrashlytics](../overview.md) |

## Permissions

`roles/firebasecrashlytics.admin` grants 17 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebasecrashlytics](permissions/firebasecrashlytics/overview.md) | 7 |
| [logging](permissions/logging/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasecrashlytics.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
