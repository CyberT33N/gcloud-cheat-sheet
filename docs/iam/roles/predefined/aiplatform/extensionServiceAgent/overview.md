# `roles/aiplatform.extensionServiceAgent`

Gives Vertex AI Extension the permissions it needs to function.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.extensionServiceAgent` |
| Title | Vertex AI Extension Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.extensionServiceAgent` grants 10 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 3 |
| [discoveryengine](permissions/discoveryengine/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.extensionServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
