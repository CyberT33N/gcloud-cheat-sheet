# `roles/beyondcorp.viewer`

Read-only access to all Cloud BeyondCorp resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/beyondcorp.viewer` |
| Title | Cloud BeyondCorp Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 30 |
| Service | [beyondcorp](../overview.md) |

## Permissions

`roles/beyondcorp.viewer` grants 30 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [beyondcorp](permissions/beyondcorp/overview.md) | 27 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |

## Inspect this role live

```shell
gcloud iam roles describe roles/beyondcorp.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
