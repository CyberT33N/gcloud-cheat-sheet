# `roles/firebaseinappmessaging.admin`

Full read/write access to Firebase In-App Messaging resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaseinappmessaging.admin` |
| Title | Firebase In-App Messaging Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 10 |
| Service | [firebaseinappmessaging](../overview.md) |

## Permissions

`roles/firebaseinappmessaging.admin` grants 10 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebaseinappmessaging](permissions/firebaseinappmessaging/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaseinappmessaging.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
