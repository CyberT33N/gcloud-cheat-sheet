# `roles/connectors.admin`

Full access to all resources of Connectors Service.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/connectors.admin` |
| Title | Connector Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 78 |
| Service | [connectors](../overview.md) |

## Permissions

`roles/connectors.admin` grants 78 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [connectors](permissions/connectors/overview.md) | 75 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [secretmanager](permissions/secretmanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/connectors.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
