# `roles/memorystore.admin`

Full access to Memorystore resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/memorystore.admin` |
| Title | Memorystore Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 28 |
| Service | [memorystore](../overview.md) |

## Permissions

`roles/memorystore.admin` grants 28 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [memorystore](permissions/memorystore/overview.md) | 21 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/memorystore.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
