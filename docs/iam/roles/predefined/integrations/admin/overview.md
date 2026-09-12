# `roles/integrations.admin`

Admin role for integrations

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/integrations.admin` |
| Title | Integrations Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 109 |
| Service | [integrations](../overview.md) |

## Permissions

`roles/integrations.admin` grants 109 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [integrations](permissions/integrations/overview.md) | 107 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/integrations.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
