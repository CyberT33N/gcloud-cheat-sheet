# `roles/integrations.apigeeIntegrationAdminRole`

A user that has full access to all Apigee integrations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/integrations.apigeeIntegrationAdminRole` |
| Title | Apigee Integration Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 83 |
| Service | [integrations](../overview.md) |

## Permissions

`roles/integrations.apigeeIntegrationAdminRole` grants 83 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [connectors](permissions/connectors/overview.md) | 11 |
| [integrations](permissions/integrations/overview.md) | 70 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/integrations.apigeeIntegrationAdminRole --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
