# `roles/firebasenotifications.admin`

Full read/write access to Firebase Cloud Messaging resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasenotifications.admin` |
| Title | Firebase Cloud Messaging Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [firebasenotifications](../overview.md) |

## Permissions

`roles/firebasenotifications.admin` grants 11 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [fcmdata](permissions/fcmdata/overview.md) | 1 |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebasenotifications](permissions/firebasenotifications/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasenotifications.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
