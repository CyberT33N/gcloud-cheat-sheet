# `roles/managedidentities.peeringViewer`

Read-only access to Google Cloud Managed Identities Peering and related resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/managedidentities.peeringViewer` |
| Title | Google Cloud Managed Identities Peering Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [managedidentities](../overview.md) |

## Permissions

`roles/managedidentities.peeringViewer` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [managedidentities](permissions/managedidentities/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/managedidentities.peeringViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
