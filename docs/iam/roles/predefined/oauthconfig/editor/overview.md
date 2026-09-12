# `roles/oauthconfig.editor`

Read/write access to OAuth config resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/oauthconfig.editor` |
| Title | OAuth Config Editor |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 28 |
| Service | [oauthconfig](../overview.md) |

## Permissions

`roles/oauthconfig.editor` grants 28 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [clientauthconfig](permissions/clientauthconfig/overview.md) | 14 |
| [firebase](permissions/firebase/overview.md) | 4 |
| [firebaseappcheck](permissions/firebaseappcheck/overview.md) | 2 |
| [oauthconfig](permissions/oauthconfig/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/oauthconfig.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
