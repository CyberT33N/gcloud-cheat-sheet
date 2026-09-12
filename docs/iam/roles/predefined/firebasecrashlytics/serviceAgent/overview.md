# `roles/firebasecrashlytics.serviceAgent`

Access to BigQuery export for Crashlytics

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasecrashlytics.serviceAgent` |
| Title | Firebase Crashlytics Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [firebasecrashlytics](../overview.md) |

## Permissions

`roles/firebasecrashlytics.serviceAgent` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 7 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasecrashlytics.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
