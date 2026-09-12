# `roles/actions.Viewer`

Access to view an action

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/actions.Viewer` |
| Title | Actions Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [actions](../overview.md) |

## Permissions

`roles/actions.Viewer` grants 7 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [actions](permissions/actions/overview.md) | 3 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/actions.Viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
