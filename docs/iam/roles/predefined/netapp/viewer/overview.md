# `roles/netapp.viewer`

Readonly access to Google Cloud NetApp Volumes resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/netapp.viewer` |
| Title | Google Cloud NetApp Volumes Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 30 |
| Service | [netapp](../overview.md) |

## Permissions

`roles/netapp.viewer` grants 30 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [netapp](permissions/netapp/overview.md) | 28 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/netapp.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
