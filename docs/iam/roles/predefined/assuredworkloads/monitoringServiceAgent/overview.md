# `roles/assuredworkloads.monitoringServiceAgent`

Gives the Assured Workloads service account access to create CAIS feed and monitor Assured Workloads.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/assuredworkloads.monitoringServiceAgent` |
| Title | Assured Workloads Monitoring Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [assuredworkloads](../overview.md) |

## Permissions

`roles/assuredworkloads.monitoringServiceAgent` grants 5 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/assuredworkloads.monitoringServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
