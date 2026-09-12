# `roles/oracledatabase.networkAdmin`

Grants full access to manage all ODB Network and ODB Subnet resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/oracledatabase.networkAdmin` |
| Title | Oracle Database@Google Network Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [oracledatabase](../overview.md) |

## Permissions

`roles/oracledatabase.networkAdmin` grants 20 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [oracledatabase](permissions/oracledatabase/overview.md) | 18 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/oracledatabase.networkAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
