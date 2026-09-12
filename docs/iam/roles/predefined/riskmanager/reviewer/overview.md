# `roles/riskmanager.reviewer`

Access to review Risk Manager reports

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/riskmanager.reviewer` |
| Title | Risk Manager Report Reviewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 9 |
| Service | [riskmanager](../overview.md) |

## Permissions

`roles/riskmanager.reviewer` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [riskmanager](permissions/riskmanager/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/riskmanager.reviewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
