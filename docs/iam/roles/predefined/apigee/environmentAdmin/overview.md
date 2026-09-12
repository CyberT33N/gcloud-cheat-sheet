# `roles/apigee.environmentAdmin`

Full read/write access to apigee environment resources, including deployments.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigee.environmentAdmin` |
| Title | Apigee Environment Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 103 |
| Service | [apigee](../overview.md) |

## Permissions

`roles/apigee.environmentAdmin` grants 103 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 100 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigee.environmentAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
