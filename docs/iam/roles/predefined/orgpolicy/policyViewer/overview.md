# `roles/orgpolicy.policyViewer`

Access to view Organization Policies on resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/orgpolicy.policyViewer` |
| Title | Organization Policy Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [orgpolicy](../overview.md) |

## Permissions

`roles/orgpolicy.policyViewer` grants 5 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [orgpolicy](permissions/orgpolicy/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/orgpolicy.policyViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
