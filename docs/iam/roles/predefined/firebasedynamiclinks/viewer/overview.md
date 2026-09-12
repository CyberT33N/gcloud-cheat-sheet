# `roles/firebasedynamiclinks.viewer`

Read-only access to Firebase Dynamic Links resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasedynamiclinks.viewer` |
| Title | Firebase Dynamic Links Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [firebasedynamiclinks](../overview.md) |

## Permissions

`roles/firebasedynamiclinks.viewer` grants 11 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [firebase](permissions/firebase/overview.md) | 3 |
| [firebasedynamiclinks](permissions/firebasedynamiclinks/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasedynamiclinks.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
