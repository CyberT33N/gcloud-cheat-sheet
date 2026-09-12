# `roles/appengine.debugger`

Ability to read or manage v2 instances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/appengine.debugger` |
| Title | App Engine Managed VM Debug Access |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 14 |
| Service | [appengine](../overview.md) |

## Permissions

`roles/appengine.debugger` grants 14 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/appengine.debugger --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
