# `roles/documentai.viewer`

Grants access to view all resources and process documents in Document AI

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/documentai.viewer` |
| Title | Document AI Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 39 |
| Service | [documentai](../overview.md) |

## Permissions

`roles/documentai.viewer` grants 39 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [documentai](permissions/documentai/overview.md) | 37 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/documentai.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
