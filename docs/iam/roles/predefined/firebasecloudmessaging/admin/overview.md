# `roles/firebasecloudmessaging.admin`

Full read/write access to Firebase Cloud Messaging API resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasecloudmessaging.admin` |
| Title | Firebase Cloud Messaging API Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [firebasecloudmessaging](../overview.md) |

## Permissions

`roles/firebasecloudmessaging.admin` grants 9 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudmessaging](permissions/cloudmessaging/overview.md) | 6 |
| [fcmdata](permissions/fcmdata/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasecloudmessaging.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
