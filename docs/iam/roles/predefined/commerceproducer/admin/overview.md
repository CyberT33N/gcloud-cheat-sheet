# `roles/commerceproducer.admin`

Grants full access to all resources in Cloud Commerce Producer API.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/commerceproducer.admin` |
| Title | Commerce Producer Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 42 |
| Service | [commerceproducer](../overview.md) |

## Permissions

`roles/commerceproducer.admin` grants 42 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [commercebusinessenablement](permissions/commercebusinessenablement/overview.md) | 1 |
| [commerceproducer](permissions/commerceproducer/overview.md) | 39 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/commerceproducer.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
