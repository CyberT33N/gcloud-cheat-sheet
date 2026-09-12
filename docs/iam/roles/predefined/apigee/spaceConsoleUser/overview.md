# `roles/apigee.spaceConsoleUser`

Provides users granted permissions on an Apigee space the minimum read permissions required to manage resources in that space in the UI.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigee.spaceConsoleUser` |
| Title | Apigee Space Console User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [apigee](../overview.md) |

## Permissions

`roles/apigee.spaceConsoleUser` grants 14 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigee.spaceConsoleUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
