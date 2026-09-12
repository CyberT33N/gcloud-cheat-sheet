# `roles/securitycenter.controlServiceAgent`

Security Center Control service agent can monitor and configure GCP resources and import security findings.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.controlServiceAgent` |
| Title | Security Center Control Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 644 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.controlServiceAgent` grants 644 permissions across 20 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [accesscontextmanager](permissions/accesscontextmanager/overview.md) | 2 |
| [aiplatform](permissions/aiplatform/overview.md) | 3 |
| [bigquery](permissions/bigquery/overview.md) | 1 |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 1 |
| [cloudasset](permissions/cloudasset/overview.md) | 568 |
| [cloudsql](permissions/cloudsql/overview.md) | 2 |
| [compute](permissions/compute/overview.md) | 8 |
| [container](permissions/container/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 2 |
| [iam.googleapis.com](permissions/iam.googleapis.com/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 2 |
| [recommender](permissions/recommender/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 7 |
| [securitycenter](permissions/securitycenter/overview.md) | 12 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 8 |
| [serviceusage](permissions/serviceusage/overview.md) | 14 |
| [stackdriver](permissions/stackdriver/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.controlServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
