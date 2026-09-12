# `roles/dialogflow.reader`

Can read agent and session properties; cannot query for intent.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dialogflow.reader` |
| Title | Dialogflow API Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 77 |
| Service | [dialogflow](../overview.md) |

## Permissions

`roles/dialogflow.reader` grants 77 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dialogflow](permissions/dialogflow/overview.md) | 76 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dialogflow.reader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
