# `roles/krmapihosting.anthosApiEndpointServiceAgent`

Grants permissions to resources managed by AnthosApiEndpoint.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/krmapihosting.anthosApiEndpointServiceAgent` |
| Title | KRM API Hosting AnthosApiEndpoint Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 508 |
| Service | [krmapihosting](../overview.md) |

## Permissions

`roles/krmapihosting.anthosApiEndpointServiceAgent` grants 508 permissions across 8 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 1 |
| [container](permissions/container/overview.md) | 413 |
| [gkehub](permissions/gkehub/overview.md) | 62 |
| [iam](permissions/iam/overview.md) | 1 |
| [meshconfig](permissions/meshconfig/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 4 |
| [serviceusage](permissions/serviceusage/overview.md) | 12 |

## Inspect this role live

```shell
gcloud iam roles describe roles/krmapihosting.anthosApiEndpointServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
