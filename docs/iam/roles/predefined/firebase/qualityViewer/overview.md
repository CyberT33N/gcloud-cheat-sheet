# `roles/firebase.qualityViewer`

Read access to Firebase Quality products and Analytics.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebase.qualityViewer` |
| Title | Firebase Quality Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 45 |
| Service | [firebase](../overview.md) |

## Permissions

`roles/firebase.qualityViewer` grants 45 permissions across 13 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apikeys](permissions/apikeys/overview.md) | 2 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [firebase](permissions/firebase/overview.md) | 7 |
| [firebaseanalytics](permissions/firebaseanalytics/overview.md) | 1 |
| [firebaseappdistro](permissions/firebaseappdistro/overview.md) | 3 |
| [firebasecrash](permissions/firebasecrash/overview.md) | 1 |
| [firebasecrashlytics](permissions/firebasecrashlytics/overview.md) | 5 |
| [firebaseextensions](permissions/firebaseextensions/overview.md) | 1 |
| [firebaseperformance](permissions/firebaseperformance/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 5 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 14 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebase.qualityViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
