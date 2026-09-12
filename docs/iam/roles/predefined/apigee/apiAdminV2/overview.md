# `roles/apigee.apiAdminV2`

Full read/write access to all apigee API resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigee.apiAdminV2` |
| Title | Apigee API Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 104 |
| Service | [apigee](../overview.md) |

## Permissions

`roles/apigee.apiAdminV2` grants 104 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 53 |
| [apihub](permissions/apihub/overview.md) | 49 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigee.apiAdminV2 --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
