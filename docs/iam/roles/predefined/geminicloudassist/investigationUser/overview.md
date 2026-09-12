# `roles/geminicloudassist.investigationUser`

Grants the ability to list existing investigations that you have permission to view and check the status of investigations. Access to individual investigations must be granted separately.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/geminicloudassist.investigationUser` |
| Title | Gemini Cloud Assist Investigation User |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 577 |
| Service | [geminicloudassist](../overview.md) |

## Permissions

`roles/geminicloudassist.investigationUser` grants 577 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 2 |
| [cloudasset](permissions/cloudasset/overview.md) | 563 |
| [geminicloudassist](permissions/geminicloudassist/overview.md) | 5 |
| [recommender](permissions/recommender/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/geminicloudassist.investigationUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
