# `roles/networksecurity.interceptEndpointViewer`

Enables read-only access to intercept resources on the Consumer's side.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/networksecurity.interceptEndpointViewer` |
| Title | Intercept Endpoint Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 6 |
| Service | [networksecurity](../overview.md) |

## Permissions

`roles/networksecurity.interceptEndpointViewer` grants 6 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [networksecurity](permissions/networksecurity/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/networksecurity.interceptEndpointViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
