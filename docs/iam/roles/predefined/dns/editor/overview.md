# `roles/dns.editor`

Editor role for DNS resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dns.editor` |
| Title | DNS Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 47 |
| Service | [dns](../overview.md) |

## Permissions

`roles/dns.editor` grants 47 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 2 |
| [dns](permissions/dns/overview.md) | 43 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dns.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
