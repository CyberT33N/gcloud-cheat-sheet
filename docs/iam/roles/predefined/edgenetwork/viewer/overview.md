# `roles/edgenetwork.viewer`

Read-only access to Edge Network all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/edgenetwork.viewer` |
| Title | Edge Network Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 29 |
| Service | [edgenetwork](../overview.md) |

## Permissions

`roles/edgenetwork.viewer` grants 29 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [edgenetwork](permissions/edgenetwork/overview.md) | 27 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/edgenetwork.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
