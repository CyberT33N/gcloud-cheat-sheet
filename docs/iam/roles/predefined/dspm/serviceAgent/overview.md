# `roles/dspm.serviceAgent`

Gives DSPM Service Account access to consumer resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dspm.serviceAgent` |
| Title | DSPM Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 87 |
| Service | [dspm](../overview.md) |

## Permissions

`roles/dspm.serviceAgent` grants 87 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 13 |
| [bigquery](permissions/bigquery/overview.md) | 11 |
| [cloudasset](permissions/cloudasset/overview.md) | 8 |
| [cloudsecuritycompliance](permissions/cloudsecuritycompliance/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 21 |
| [securitycenter](permissions/securitycenter/overview.md) | 3 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 5 |
| [securityposture](permissions/securityposture/overview.md) | 7 |
| [serviceusage](permissions/serviceusage/overview.md) | 3 |
| [storage](permissions/storage/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dspm.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
