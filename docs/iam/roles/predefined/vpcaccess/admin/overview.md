# `roles/vpcaccess.admin`

Full access to all Serverless VPC Access resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vpcaccess.admin` |
| Title | Serverless VPC Access Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [vpcaccess](../overview.md) |

## Permissions

`roles/vpcaccess.admin` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [vpcaccess](permissions/vpcaccess/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vpcaccess.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
