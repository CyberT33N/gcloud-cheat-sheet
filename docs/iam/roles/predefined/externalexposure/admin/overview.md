# `roles/externalexposure.admin`

Full access to external exposure resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/externalexposure.admin` |
| Title | External Exposure Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 9 |
| Service | [externalexposure](../overview.md) |

## Permissions

`roles/externalexposure.admin` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [externalexposure](permissions/externalexposure/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/externalexposure.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
