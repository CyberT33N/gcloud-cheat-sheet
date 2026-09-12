# `roles/workloadcertificate.admin`

Full access to all Workload Certificate API resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workloadcertificate.admin` |
| Title | Workload Certificate Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 15 |
| Service | [workloadcertificate](../overview.md) |

## Permissions

`roles/workloadcertificate.admin` grants 15 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [workloadcertificate](permissions/workloadcertificate/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workloadcertificate.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
