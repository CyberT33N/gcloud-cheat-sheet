# `roles/notebooks.legacyViewer`

Read-only access to Notebooks all resources through compute API.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/notebooks.legacyViewer` |
| Title | Notebooks Legacy Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 447 |
| Service | [notebooks](../overview.md) |

## Permissions

`roles/notebooks.legacyViewer` grants 447 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 412 |
| [notebooks](permissions/notebooks/overview.md) | 23 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/notebooks.legacyViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
