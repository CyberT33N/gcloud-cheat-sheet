# `roles/dataproc.admin`

Full control of Dataproc resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataproc.admin` |
| Title | Dataproc Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 98 |
| Service | [dataproc](../overview.md) |

## Permissions

`roles/dataproc.admin` grants 98 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 9 |
| [dataproc](permissions/dataproc/overview.md) | 65 |
| [dataprocrm](permissions/dataprocrm/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataproc.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
