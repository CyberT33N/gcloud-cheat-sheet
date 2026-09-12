# `roles/iap.tunnelDestGroupViewer`

View Tunnel Destination Group resources which use Identity-Aware Proxy

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iap.tunnelDestGroupViewer` |
| Title | IAP-secured Tunnel Destination Group Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [iap](../overview.md) |

## Permissions

`roles/iap.tunnelDestGroupViewer` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iap](permissions/iap/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iap.tunnelDestGroupViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
