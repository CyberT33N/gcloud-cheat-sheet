# `roles/vmwareengine.serviceAgent`

Gives permission to manage network configuration, such as establishing network peering, necessary for GCVE

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vmwareengine.serviceAgent` |
| Title | VMware Engine Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 71 |
| Service | [vmwareengine](../overview.md) |

## Permissions

`roles/vmwareengine.serviceAgent` grants 71 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 18 |
| [dns](permissions/dns/overview.md) | 43 |
| [file](permissions/file/overview.md) | 2 |
| [netapp](permissions/netapp/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [vmwareengine](permissions/vmwareengine/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vmwareengine.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
