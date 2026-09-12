# `roles/appengine.codeViewer`

Ability to view App Engine app status and deployed source code.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/appengine.codeViewer` |
| Title | App Engine Code Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [appengine](../overview.md) |

## Permissions

`roles/appengine.codeViewer` grants 14 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 11 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/appengine.codeViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
