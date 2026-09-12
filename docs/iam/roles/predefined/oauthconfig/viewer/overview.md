# `roles/oauthconfig.viewer`

Read-only access to OAuth config resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/oauthconfig.viewer` |
| Title | OAuth Config Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 12 |
| Service | [oauthconfig](../overview.md) |

## Permissions

`roles/oauthconfig.viewer` grants 12 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [clientauthconfig](permissions/clientauthconfig/overview.md) | 4 |
| [firebase](permissions/firebase/overview.md) | 2 |
| [firebaseappcheck](permissions/firebaseappcheck/overview.md) | 1 |
| [oauthconfig](permissions/oauthconfig/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/oauthconfig.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
