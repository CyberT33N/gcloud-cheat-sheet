# `roles/dataplex.securityAdmin`

Permissions configure ResourceAccess and DataAccess Specs on Data Attributes.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.securityAdmin` |
| Title | Dataplex Security Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.securityAdmin` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataplex](permissions/dataplex/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.securityAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
