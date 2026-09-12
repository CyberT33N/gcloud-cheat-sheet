# `roles/firebase.growthViewer`

Read access to Firebase Grow products and Analytics.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebase.growthViewer` |
| Title | Firebase Grow Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 50 |
| Service | [firebase](../overview.md) |

## Permissions

`roles/firebase.growthViewer` grants 50 permissions across 16 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apikeys](permissions/apikeys/overview.md) | 2 |
| [cloudconfig](permissions/cloudconfig/overview.md) | 1 |
| [cloudmessaging](permissions/cloudmessaging/overview.md) | 2 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [fcmdata](permissions/fcmdata/overview.md) | 1 |
| [firebase](permissions/firebase/overview.md) | 7 |
| [firebaseabt](permissions/firebaseabt/overview.md) | 4 |
| [firebaseanalytics](permissions/firebaseanalytics/overview.md) | 1 |
| [firebasedynamiclinks](permissions/firebasedynamiclinks/overview.md) | 6 |
| [firebaseextensions](permissions/firebaseextensions/overview.md) | 1 |
| [firebaseinappmessaging](permissions/firebaseinappmessaging/overview.md) | 2 |
| [firebasemessagingcampaigns](permissions/firebasemessagingcampaigns/overview.md) | 2 |
| [firebasenotifications](permissions/firebasenotifications/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 14 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebase.growthViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
