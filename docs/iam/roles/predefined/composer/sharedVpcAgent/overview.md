# `roles/composer.sharedVpcAgent`

Role that should be assigned to Composer Agent service account in Shared VPC host project

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/composer.sharedVpcAgent` |
| Title | Composer Shared VPC Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 25 |
| Service | [composer](../overview.md) |

## Permissions

`roles/composer.sharedVpcAgent` grants 25 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 22 |
| [dns](permissions/dns/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/composer.sharedVpcAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
