# `roles/translationhub.portalUser`

Portal user of Translation Hub

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/translationhub.portalUser` |
| Title | Translation Hub Portal User |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 13 |
| Service | [translationhub](../overview.md) |

## Permissions

`roles/translationhub.portalUser` grants 13 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automl](permissions/automl/overview.md) | 3 |
| [cloudtranslate](permissions/cloudtranslate/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [translationhub](permissions/translationhub/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/translationhub.portalUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
