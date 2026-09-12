# `roles/aiplatform.extensionCustomCodeServiceAgent`

Gives Vertex AI Extension that executes custom code the permissions it needs to function.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/aiplatform.extensionCustomCodeServiceAgent` |
| Title | Vertex AI Extension Custom Code Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 34 |
| Service | [aiplatform](../overview.md) |

## Permissions

`roles/aiplatform.extensionCustomCodeServiceAgent` grants 34 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 28 |

## Inspect this role live

```shell
gcloud iam roles describe roles/aiplatform.extensionCustomCodeServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
