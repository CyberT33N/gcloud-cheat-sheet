# `roles/translationhub.admin`

Admin of Translation Hub

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/translationhub.admin` |
| Title | Translation Hub Admin |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 18 |
| Service | [translationhub](../overview.md) |

## Permissions

`roles/translationhub.admin` grants 18 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automl](permissions/automl/overview.md) | 3 |
| [cloudtranslate](permissions/cloudtranslate/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [translationhub](permissions/translationhub/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/translationhub.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
