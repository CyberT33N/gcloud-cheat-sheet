# `roles/analyticshub.publisher`

Can publish to Data Exchanges thus creating Listings

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/analyticshub.publisher` |
| Title | Analytics Hub Publisher |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [analyticshub](../overview.md) |

## Permissions

`roles/analyticshub.publisher` grants 15 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [analyticshub](permissions/analyticshub/overview.md) | 13 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/analyticshub.publisher --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
