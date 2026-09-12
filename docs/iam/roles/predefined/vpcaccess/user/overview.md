# `roles/vpcaccess.user`

User of Serverless VPC Access connectors

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vpcaccess.user` |
| Title | Serverless VPC Access User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [vpcaccess](../overview.md) |

## Permissions

`roles/vpcaccess.user` grants 8 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [vpcaccess](permissions/vpcaccess/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vpcaccess.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
