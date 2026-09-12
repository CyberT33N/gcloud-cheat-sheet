# `roles/bigtable.admin`

Full access to all Bigtable resources and ability to assign Bigtable IAM roles.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigtable.admin` |
| Title | Bigtable Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 100 |
| Service | [bigtable](../overview.md) |

## Permissions

`roles/bigtable.admin` grants 100 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigtable](permissions/bigtable/overview.md) | 90 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [monitoring](permissions/monitoring/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigtable.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
