# `roles/securitycenter.attackSurfaceManagementScannerServiceAgent`

Gives Mandiant Attack Surface Management the ability to scan Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.attackSurfaceManagementScannerServiceAgent` |
| Title | Attack Surface Management Scanner Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.attackSurfaceManagementScannerServiceAgent` grants 5 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigateway](permissions/apigateway/overview.md) | 1 |
| [cloudasset](permissions/cloudasset/overview.md) | 1 |
| [dns](permissions/dns/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.attackSurfaceManagementScannerServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
