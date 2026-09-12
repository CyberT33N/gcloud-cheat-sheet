# `roles/connectors.customConnectorAdmin`

Custom Connector  is a global resource which creates custom connector within the given target project. This role grants Admin access to Custom Connector resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/connectors.customConnectorAdmin` |
| Title | Custom Connectors Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [connectors](../overview.md) |

## Permissions

`roles/connectors.customConnectorAdmin` grants 16 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [connectors](permissions/connectors/overview.md) | 16 |

## Inspect this role live

```shell
gcloud iam roles describe roles/connectors.customConnectorAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
