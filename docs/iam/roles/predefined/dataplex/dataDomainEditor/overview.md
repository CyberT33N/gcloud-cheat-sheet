# `roles/dataplex.dataDomainEditor`

Allows updating the Data Domain as well as full management of its bindings.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.dataDomainEditor` |
| Title | Dataplex Data Domain Configuration Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 13 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.dataDomainEditor` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataplex](permissions/dataplex/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.dataDomainEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
