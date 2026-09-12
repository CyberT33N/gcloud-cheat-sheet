# `roles/bigquerydatapolicy.maskedReader`

Masked read access to sub-resources tagged by the policy tag associated with a data policy, for example, BigQuery columns

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/bigquerydatapolicy.maskedReader` |
| Title | Masked Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [bigquerydatapolicy](../overview.md) |

## Permissions

`roles/bigquerydatapolicy.maskedReader` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/bigquerydatapolicy.maskedReader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
