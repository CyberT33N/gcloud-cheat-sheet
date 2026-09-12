# `roles/dns.serviceAgent`

Gives Cloud DNS Service Agent access to Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dns.serviceAgent` |
| Title | Cloud DNS Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [dns](../overview.md) |

## Permissions

`roles/dns.serviceAgent` grants 7 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dns.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
