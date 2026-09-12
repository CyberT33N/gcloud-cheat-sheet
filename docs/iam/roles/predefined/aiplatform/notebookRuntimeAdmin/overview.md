# `roles/aiplatform.notebookRuntimeAdmin`

Grants full access to all runtime templates and runtimes in Notebook Service.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.notebookRuntimeAdmin` |
| Title | Notebook Runtime Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.notebookRuntimeAdmin` grants 20 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 18 |
| [compute](permissions/compute/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.notebookRuntimeAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
