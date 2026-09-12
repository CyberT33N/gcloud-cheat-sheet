# `roles/saasservicemgmt.admin`

Provide full access to all SaaS Service Management resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/saasservicemgmt.admin` |
| Title | SaaS Service Management Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 98 |
| Service | [saasservicemgmt](../overview.md) |

## Permissions

`roles/saasservicemgmt.admin` grants 98 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [saasservicemgmt](permissions/saasservicemgmt/overview.md) | 96 |

## Inspect this role live

```shell
gcloud iam roles describe roles/saasservicemgmt.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
