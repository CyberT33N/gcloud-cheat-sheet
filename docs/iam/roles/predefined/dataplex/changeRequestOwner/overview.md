# `roles/dataplex.changeRequestOwner`

Grants Change Request creator necessary permissions on a created ChangeRequest instance.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataplex.changeRequestOwner` |
| Title | Dataplex Change Request Owner |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 3 |
| Service | [dataplex](../overview.md) |

## Permissions

`roles/dataplex.changeRequestOwner` grants 3 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [dataplex](permissions/dataplex/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataplex.changeRequestOwner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
