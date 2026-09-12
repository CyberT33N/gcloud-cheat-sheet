# `roles/securitycenter.securityHealthAnalyticsServiceAgent`

Security Health Analytics service agent can scan GCP resource metadata to find security vulnerabilities.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.securityHealthAnalyticsServiceAgent` |
| Title | Security Health Analytics Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 598 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.securityHealthAnalyticsServiceAgent` grants 598 permissions across 13 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 1 |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 1 |
| [cloudasset](permissions/cloudasset/overview.md) | 568 |
| [cloudsql](permissions/cloudsql/overview.md) | 2 |
| [compute](permissions/compute/overview.md) | 5 |
| [container](permissions/container/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securitycenter](permissions/securitycenter/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [stackdriver](permissions/stackdriver/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.securityHealthAnalyticsServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
