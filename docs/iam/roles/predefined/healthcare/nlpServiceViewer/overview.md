# `roles/healthcare.nlpServiceViewer`

Extract and analyze medical entities from a given text.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/healthcare.nlpServiceViewer` |
| Title | Healthcare NLP Service Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 5 |
| Service | [healthcare](../overview.md) |

## Permissions

`roles/healthcare.nlpServiceViewer` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [healthcare](permissions/healthcare/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/healthcare.nlpServiceViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
