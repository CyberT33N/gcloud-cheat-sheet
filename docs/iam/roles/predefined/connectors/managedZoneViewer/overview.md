# `roles/connectors.managedZoneViewer`

Managed Zone is a global resource which creates Cloud DNS Peering Zone with the given target project. This role grants Read-only access to Connectors Managed Zone resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/connectors.managedZoneViewer` |
| Title | Connectors Managed Zone Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [connectors](../overview.md) |

## Permissions

`roles/connectors.managedZoneViewer` grants 5 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [connectors](permissions/connectors/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/connectors.managedZoneViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
