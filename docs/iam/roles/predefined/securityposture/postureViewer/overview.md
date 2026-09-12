# `roles/securityposture.postureViewer`

Read only access to the Posture resource.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securityposture.postureViewer` |
| Title | Security Posture Resource Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [securityposture](../overview.md) |

## Permissions

`roles/securityposture.postureViewer` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [securityposture](permissions/securityposture/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securityposture.postureViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
