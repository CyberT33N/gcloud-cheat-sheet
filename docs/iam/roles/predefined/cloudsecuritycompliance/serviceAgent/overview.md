# `roles/cloudsecuritycompliance.serviceAgent`

Gives CSC Service Account access to consumer resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsecuritycompliance.serviceAgent` |
| Title | Cloud Security Compliance Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 702 |
| Service | [cloudsecuritycompliance](../overview.md) |

## Permissions

`roles/cloudsecuritycompliance.serviceAgent` grants 702 permissions across 27 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [accessapproval](permissions/accessapproval/overview.md) | 1 |
| [aiplatform](permissions/aiplatform/overview.md) | 20 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 2 |
| [axt](permissions/axt/overview.md) | 1 |
| [bigquery](permissions/bigquery/overview.md) | 1 |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 1 |
| [certificatemanager](permissions/certificatemanager/overview.md) | 2 |
| [cloudasset](permissions/cloudasset/overview.md) | 566 |
| [cloudkms](permissions/cloudkms/overview.md) | 3 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 13 |
| [cloudsecurityscanner](permissions/cloudsecurityscanner/overview.md) | 2 |
| [cloudsql](permissions/cloudsql/overview.md) | 4 |
| [compute](permissions/compute/overview.md) | 27 |
| [container](permissions/container/overview.md) | 2 |
| [dlp](permissions/dlp/overview.md) | 5 |
| [dns](permissions/dns/overview.md) | 1 |
| [iam](permissions/iam/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 2 |
| [notebooks](permissions/notebooks/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 2 |
| [privateca](permissions/privateca/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 15 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 16 |
| [storage](permissions/storage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsecuritycompliance.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
