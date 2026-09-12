# `roles/binaryauthorization.policyViewer`

Viewer of Binary Authorization Policy

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/binaryauthorization.policyViewer` |
| Title | Binary Authorization Policy Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 6 |
| Service | [binaryauthorization](../overview.md) |

## Permissions

`roles/binaryauthorization.policyViewer` grants 6 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/binaryauthorization.policyViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
