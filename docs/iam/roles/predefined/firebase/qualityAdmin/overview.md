# `roles/firebase.qualityAdmin`

Full access to Firebase Quality products and Analytics.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebase.qualityAdmin` |
| Title | Firebase Quality Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 53 |
| Service | [firebase](../overview.md) |

## Permissions

`roles/firebase.qualityAdmin` grants 53 permissions across 13 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apikeys](permissions/apikeys/overview.md) | 2 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [firebase](permissions/firebase/overview.md) | 7 |
| [firebaseanalytics](permissions/firebaseanalytics/overview.md) | 2 |
| [firebaseappdistro](permissions/firebaseappdistro/overview.md) | 6 |
| [firebasecrash](permissions/firebasecrash/overview.md) | 2 |
| [firebasecrashlytics](permissions/firebasecrashlytics/overview.md) | 7 |
| [firebaseextensions](permissions/firebaseextensions/overview.md) | 1 |
| [firebaseperformance](permissions/firebaseperformance/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 5 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 14 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebase.qualityAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
