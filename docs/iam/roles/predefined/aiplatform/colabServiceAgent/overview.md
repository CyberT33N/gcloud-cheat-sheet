# `roles/aiplatform.colabServiceAgent`

Gives Vertex AI Colab the proper permissions to function.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.colabServiceAgent` |
| Title | Vertex AI Colab Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 45 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.colabServiceAgent` grants 45 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 40 |
| [iam](permissions/iam/overview.md) | 1 |
| [notebooks](permissions/notebooks/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.colabServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
