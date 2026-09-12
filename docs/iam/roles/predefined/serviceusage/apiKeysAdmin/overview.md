# `roles/serviceusage.apiKeysAdmin`

Ability to create, delete, update, get and list API keys for a project.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/serviceusage.apiKeysAdmin` |
| Title | API Keys Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [serviceusage](../overview.md) |

## Permissions

`roles/serviceusage.apiKeysAdmin` grants 12 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apikeys](permissions/apikeys/overview.md) | 8 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/serviceusage.apiKeysAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
