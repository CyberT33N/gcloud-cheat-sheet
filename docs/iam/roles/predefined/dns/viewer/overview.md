# `roles/dns.viewer`

Viewer role for DNS resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dns.viewer` |
| Title | DNS Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [dns](../overview.md) |

## Permissions

`roles/dns.viewer` grants 23 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 1 |
| [dns](permissions/dns/overview.md) | 20 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dns.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
