# `roles/networksecurity.firewallEndpointAdmin`

Enables full access to firewall endpoint and firewall endpoint association resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/networksecurity.firewallEndpointAdmin` |
| Title | Firewall Endpoint Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 22 |
| Service | [networksecurity](../overview.md) |

## Permissions

`roles/networksecurity.firewallEndpointAdmin` grants 22 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [networksecurity](permissions/networksecurity/overview.md) | 20 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/networksecurity.firewallEndpointAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
