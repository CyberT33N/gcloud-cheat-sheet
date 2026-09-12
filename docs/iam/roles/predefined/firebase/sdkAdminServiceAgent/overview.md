# `roles/firebase.sdkAdminServiceAgent`

Read and write access to Firebase products available in the Admin SDK

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebase.sdkAdminServiceAgent` |
| Title | Firebase Admin SDK Administrator Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 182 |
| Service | [firebase](../overview.md) |

## Permissions

`roles/firebase.sdkAdminServiceAgent` grants 182 permissions across 19 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [cloudconfig](permissions/cloudconfig/overview.md) | 2 |
| [cloudmessaging](permissions/cloudmessaging/overview.md) | 1 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 6 |
| [datastore](permissions/datastore/overview.md) | 16 |
| [firebase](permissions/firebase/overview.md) | 8 |
| [firebaseappcheck](permissions/firebaseappcheck/overview.md) | 27 |
| [firebaseauth](permissions/firebaseauth/overview.md) | 10 |
| [firebasedatabase](permissions/firebasedatabase/overview.md) | 8 |
| [firebasedataconnect](permissions/firebasedataconnect/overview.md) | 32 |
| [firebasehosting](permissions/firebasehosting/overview.md) | 5 |
| [firebaseml](permissions/firebaseml/overview.md) | 9 |
| [firebasenotifications](permissions/firebasenotifications/overview.md) | 5 |
| [firebaserules](permissions/firebaserules/overview.md) | 7 |
| [identitytoolkit](permissions/identitytoolkit/overview.md) | 7 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [storage](permissions/storage/overview.md) | 33 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebase.sdkAdminServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
