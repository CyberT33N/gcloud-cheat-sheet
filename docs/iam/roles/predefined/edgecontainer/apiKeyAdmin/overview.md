# `roles/edgecontainer.apiKeyAdmin`

Access to manage API Keys.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/edgecontainer.apiKeyAdmin` |
| Title | Edge Container API Key Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [edgecontainer](../overview.md) |

## Permissions

`roles/edgecontainer.apiKeyAdmin` grants 10 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [edgecontainer](permissions/edgecontainer/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/edgecontainer.apiKeyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
