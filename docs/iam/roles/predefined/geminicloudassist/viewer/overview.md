# `roles/geminicloudassist.viewer`

Grants the ability to view Gemini Cloud Assist chat and create investigations.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/geminicloudassist.viewer` |
| Title | Gemini Cloud Assist Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 69 |
| Service | [geminicloudassist](../overview.md) |

## Permissions

`roles/geminicloudassist.viewer` grants 69 permissions across 9 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apphub](permissions/apphub/overview.md) | 4 |
| [appoptimize](permissions/appoptimize/overview.md) | 2 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 2 |
| [config](permissions/config/overview.md) | 16 |
| [designcenter](permissions/designcenter/overview.md) | 29 |
| [geminicloudassist](permissions/geminicloudassist/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/geminicloudassist.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
