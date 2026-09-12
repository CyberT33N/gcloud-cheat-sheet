# `roles/securitycenter.assetsViewer`

Read access to assets

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.assetsViewer` |
| Title | Security Center Assets Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.assetsViewer` grants 20 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 13 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [securitycenter](permissions/securitycenter/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.assetsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
