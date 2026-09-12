# `roles/cloudtranslate.serviceAgent`

Gives Cloud Translation Service Account access to consumer resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtranslate.serviceAgent` |
| Title | Cloud Translation API Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [cloudtranslate](../overview.md) |

## Permissions

`roles/cloudtranslate.serviceAgent` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [automl](permissions/automl/overview.md) | 6 |
| [storage](permissions/storage/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtranslate.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
