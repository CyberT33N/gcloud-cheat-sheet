# `roles/workstations.networkAdmin`

Grants ability to connect a Workstation Cluster to a shared VPC network.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workstations.networkAdmin` |
| Title | Cloud Workstations Network Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 25 |
| Service | [workstations](../overview.md) |

## Permissions

`roles/workstations.networkAdmin` grants 25 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 21 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workstations.networkAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
