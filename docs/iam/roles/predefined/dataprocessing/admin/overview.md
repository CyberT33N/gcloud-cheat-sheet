# `roles/dataprocessing.admin`

Data processing controls admin who can fully manage data processing controls settings and view all datasource data.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/dataprocessing.admin` |
| Title | Data Processing Controls Resource Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [dataprocessing](../overview.md) |

## Permissions

`roles/dataprocessing.admin` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [billing](permissions/billing/overview.md) | 2 |
| [dataprocessing](permissions/dataprocessing/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/dataprocessing.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
