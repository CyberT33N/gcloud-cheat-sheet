# `roles/dialogflow.admin`

Can query for intent; read & write session properties; read & write agent properties.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dialogflow.admin` |
| Title | Dialogflow API Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 194 |
| Service | [dialogflow](../overview.md) |

## Permissions

`roles/dialogflow.admin` grants 194 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dialogflow](permissions/dialogflow/overview.md) | 193 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dialogflow.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
