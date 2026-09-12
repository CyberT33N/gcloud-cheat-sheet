# `roles/apigee.readOnlyAdmin`

Viewer of all apigee resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigee.readOnlyAdmin` |
| Title | Apigee Read-only Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 140 |
| Service | [apigee](../overview.md) |

## Permissions

`roles/apigee.readOnlyAdmin` grants 140 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 136 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigee.readOnlyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
