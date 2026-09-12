# `roles/policyanalyzer.admin`

Admin role for policyanalyzer

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/policyanalyzer.admin` |
| Title | Policyanalyzer Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 5 |
| Service | [policyanalyzer](../overview.md) |

## Permissions

`roles/policyanalyzer.admin` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [policyanalyzer](permissions/policyanalyzer/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/policyanalyzer.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
