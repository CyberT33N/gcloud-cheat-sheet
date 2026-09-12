# `roles/cloudtranslate.user`

User of Cloud Translation and AutoML models

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtranslate.user` |
| Title | Cloud Translation API User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 34 |
| Service | [cloudtranslate](../overview.md) |

## Permissions

`roles/cloudtranslate.user` grants 34 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automl](permissions/automl/overview.md) | 2 |
| [cloudtranslate](permissions/cloudtranslate/overview.md) | 30 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtranslate.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
