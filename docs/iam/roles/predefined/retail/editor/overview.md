# `roles/retail.editor`

Full access to Retail api resources except purge, rejoin, and setSponsorship.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/retail.editor` |
| Title | Retail Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 97 |
| Service | [retail](../overview.md) |

## Permissions

`roles/retail.editor` grants 97 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automlrecommendations](permissions/automlrecommendations/overview.md) | 23 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [retail](permissions/retail/overview.md) | 71 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/retail.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
