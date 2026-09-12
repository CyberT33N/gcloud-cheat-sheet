# `roles/spectrumsas.serviceAgent`

Gives Spectrum SAS Service Account access to enable analytics on behalf of users.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/spectrumsas.serviceAgent` |
| Title | Spectrum SAS Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 39 |
| Service | [spectrumsas](../overview.md) |

## Permissions

`roles/spectrumsas.serviceAgent` grants 39 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [bigquery](permissions/bigquery/overview.md) | 4 |
| [pubsub](permissions/pubsub/overview.md) | 31 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/spectrumsas.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
