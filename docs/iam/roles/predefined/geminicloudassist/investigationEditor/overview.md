# `roles/geminicloudassist.investigationEditor`

Grants the ability to list, view, edit, and run existing Gemini Cloud Assist investigations. The ability to create or delete an investigation is granted separately.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/geminicloudassist.investigationEditor` |
| Title | Gemini Cloud Assist Investigation Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 584 |
| Service | [geminicloudassist](../overview.md) |

## Permissions

`roles/geminicloudassist.investigationEditor` grants 584 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 2 |
| [cloudasset](permissions/cloudasset/overview.md) | 563 |
| [geminicloudassist](permissions/geminicloudassist/overview.md) | 12 |
| [recommender](permissions/recommender/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/geminicloudassist.investigationEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
