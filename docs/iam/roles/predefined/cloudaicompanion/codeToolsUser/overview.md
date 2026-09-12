# `roles/cloudaicompanion.codeToolsUser`

Grants read access to Gemini Code Assist Tools resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudaicompanion.codeToolsUser` |
| Title | Gemini Code Assist Tools User |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 36 |
| Service | [cloudaicompanion](../overview.md) |

## Permissions

`roles/cloudaicompanion.codeToolsUser` grants 36 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 17 |
| [developerconnect](permissions/developerconnect/overview.md) | 16 |
| [geminicloudassist](permissions/geminicloudassist/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudaicompanion.codeToolsUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
