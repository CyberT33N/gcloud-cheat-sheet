# `roles/notebooks.editor`

Editor role for notebooks

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/notebooks.editor` |
| Title | Notebooks Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 482 |
| Service | [notebooks](../overview.md) |

## Permissions

`roles/notebooks.editor` grants 482 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 4 |
| [compute](permissions/compute/overview.md) | 412 |
| [notebooks](permissions/notebooks/overview.md) | 54 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/notebooks.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
