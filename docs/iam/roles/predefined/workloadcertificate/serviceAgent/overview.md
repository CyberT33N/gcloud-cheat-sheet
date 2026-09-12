# `roles/workloadcertificate.serviceAgent`

Gives the Workload Certificate service agent access to Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workloadcertificate.serviceAgent` |
| Title | Workload Certificate Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 24 |
| Service | [workloadcertificate](../overview.md) |

## Permissions

`roles/workloadcertificate.serviceAgent` grants 24 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [container](permissions/container/overview.md) | 9 |
| [gkehub](permissions/gkehub/overview.md) | 8 |
| [serviceconsumermanagement](permissions/serviceconsumermanagement/overview.md) | 4 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [workloadcertificate](permissions/workloadcertificate/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workloadcertificate.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
