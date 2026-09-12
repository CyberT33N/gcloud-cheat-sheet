# `roles/compute.serviceAgent`

Gives Compute Engine Service Account access to assert service account authority. Includes access to service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.serviceAgent` |
| Title | Compute Engine Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 100 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.serviceAgent` grants 100 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 55 |
| [iam](permissions/iam/overview.md) | 5 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 29 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
