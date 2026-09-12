# `roles/firebasecrashlytics.viewer`

Read-only access to Firebase Crashlytics resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasecrashlytics.viewer` |
| Title | Firebase Crashlytics Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [firebasecrashlytics](../overview.md) |

## Permissions

`roles/firebasecrashlytics.viewer` grants 15 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebasecrashlytics](permissions/firebasecrashlytics/overview.md) | 5 |
| [logging](permissions/logging/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasecrashlytics.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
