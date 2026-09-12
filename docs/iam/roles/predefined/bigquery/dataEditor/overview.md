# `roles/bigquery.dataEditor`

Access to edit all the contents of datasets

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquery.dataEditor` |
| Title | BigQuery Data Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 59 |
| Service | [bigquery](../overview.md) |

## Permissions

`roles/bigquery.dataEditor` grants 59 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 41 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [dataplex](permissions/dataplex/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquery.dataEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
