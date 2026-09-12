# `roles/auditmanager.serviceAgent`

Grants Audit Manager Service Agent access to various list/get rpcs of products to perform an audit.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/auditmanager.serviceAgent` |
| Title | Audit Manager Auditing Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 657 |
| Service | [auditmanager](../overview.md) |

## Permissions

`roles/auditmanager.serviceAgent` grants 657 permissions across 23 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [accessapproval](permissions/accessapproval/overview.md) | 1 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 2 |
| [bigquery](permissions/bigquery/overview.md) | 1 |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 1 |
| [certificatemanager](permissions/certificatemanager/overview.md) | 2 |
| [cloudasset](permissions/cloudasset/overview.md) | 563 |
| [cloudkms](permissions/cloudkms/overview.md) | 3 |
| [cloudsecurityscanner](permissions/cloudsecurityscanner/overview.md) | 2 |
| [cloudsql](permissions/cloudsql/overview.md) | 4 |
| [compute](permissions/compute/overview.md) | 27 |
| [container](permissions/container/overview.md) | 2 |
| [dlp](permissions/dlp/overview.md) | 2 |
| [dns](permissions/dns/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 2 |
| [privateca](permissions/privateca/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 15 |
| [secretmanager](permissions/secretmanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 14 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/auditmanager.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
