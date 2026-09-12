# `roles/firebasestorage.viewer`

Read-only access for Cloud Storage for Firebase.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasestorage.viewer` |
| Title | Cloud Storage for Firebase Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 5 |
| Service | [firebasestorage](../overview.md) |

## Permissions

`roles/firebasestorage.viewer` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebasestorage](permissions/firebasestorage/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasestorage.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
