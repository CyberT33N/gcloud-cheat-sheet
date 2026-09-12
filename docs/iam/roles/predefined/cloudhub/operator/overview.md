# `roles/cloudhub.operator`

Allows users to view and interact with Cloud Hub.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudhub.operator` |
| Title | Cloud Hub Operator |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 1133 |
| Service | [cloudhub](../overview.md) |

## Permissions

`roles/cloudhub.operator` grants 1133 permissions across 28 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apphub](permissions/apphub/overview.md) | 18 |
| [apptopology](permissions/apptopology/overview.md) | 14 |
| [auditmanager](permissions/auditmanager/overview.md) | 15 |
| [billing](permissions/billing/overview.md) | 1 |
| [capacityplanner](permissions/capacityplanner/overview.md) | 8 |
| [cloudasset](permissions/cloudasset/overview.md) | 564 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [cloudquotas](permissions/cloudquotas/overview.md) | 1 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 31 |
| [cloudsupport](permissions/cloudsupport/overview.md) | 3 |
| [compute](permissions/compute/overview.md) | 4 |
| [config](permissions/config/overview.md) | 20 |
| [container](permissions/container/overview.md) | 1 |
| [designcenter](permissions/designcenter/overview.md) | 29 |
| [developerconnect](permissions/developerconnect/overview.md) | 8 |
| [errorreporting](permissions/errorreporting/overview.md) | 4 |
| [logging](permissions/logging/overview.md) | 28 |
| [maintenance](permissions/maintenance/overview.md) | 4 |
| [monitoring](permissions/monitoring/overview.md) | 29 |
| [observability](permissions/observability/overview.md) | 1 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 290 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |
| [securitycenter](permissions/securitycenter/overview.md) | 24 |
| [servicehealth](permissions/servicehealth/overview.md) | 11 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [stackdriver](permissions/stackdriver/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudhub.operator --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
