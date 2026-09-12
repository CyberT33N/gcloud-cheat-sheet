# `roles/managedidentities.serviceAgent`

Gives Managed Identities service account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedidentities.serviceAgent` |
| Title | Cloud Managed Identities Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 49 |
| Service | [managedidentities](../overview.md) |

## Permissions

`roles/managedidentities.serviceAgent` grants 49 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 6 |
| [dns](permissions/dns/overview.md) | 35 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedidentities.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
