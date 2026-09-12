# `roles/threatintelligence.ctemViewer`

This role can view all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/threatintelligence.ctemViewer` |
| Title | CTEM Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 7 |
| Service | [threatintelligence](../overview.md) |

## Permissions

`roles/threatintelligence.ctemViewer` grants 7 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [threatintelligence](permissions/threatintelligence/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/threatintelligence.ctemViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
