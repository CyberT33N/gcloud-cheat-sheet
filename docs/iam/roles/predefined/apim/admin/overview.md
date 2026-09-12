# `roles/apim.admin`

Full access to API Management resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apim.admin` |
| Title | API Management Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 25 |
| Service | [apim](../overview.md) |

## Permissions

`roles/apim.admin` grants 25 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apim](permissions/apim/overview.md) | 23 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apim.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
