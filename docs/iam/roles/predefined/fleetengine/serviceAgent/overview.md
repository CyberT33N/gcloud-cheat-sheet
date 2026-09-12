# `roles/fleetengine.serviceAgent`

Grants the FleetEngine Service Account access to manage resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/fleetengine.serviceAgent` |
| Title | FleetEngine Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [fleetengine](../overview.md) |

## Permissions

`roles/fleetengine.serviceAgent` grants 14 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 5 |
| [dataform](permissions/dataform/overview.md) | 5 |
| [geminidataanalytics](permissions/geminidataanalytics/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/fleetengine.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
