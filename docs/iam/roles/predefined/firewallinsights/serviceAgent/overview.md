# `roles/firewallinsights.serviceAgent`

Gives Cloud Firewall Insights service agent permissions to retrieve Firewall, VM and route resources on user behalf.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firewallinsights.serviceAgent` |
| Title | Cloud Firewall Insights Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [firewallinsights](../overview.md) |

## Permissions

`roles/firewallinsights.serviceAgent` grants 27 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 27 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firewallinsights.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
