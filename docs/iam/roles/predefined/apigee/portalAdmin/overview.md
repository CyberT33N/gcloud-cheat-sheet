# `roles/apigee.portalAdmin`

Portal admin for an Apigee Organization

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigee.portalAdmin` |
| Title | Apigee Portal Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [apigee](../overview.md) |

## Permissions

`roles/apigee.portalAdmin` grants 11 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigee.portalAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
