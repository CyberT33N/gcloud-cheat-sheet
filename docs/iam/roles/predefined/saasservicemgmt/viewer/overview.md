# `roles/saasservicemgmt.viewer`

Provides read-only access to SaaS Service Management resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/saasservicemgmt.viewer` |
| Title | SaaS Service Management Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 42 |
| Service | [saasservicemgmt](../overview.md) |

## Permissions

`roles/saasservicemgmt.viewer` grants 42 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [saasservicemgmt](permissions/saasservicemgmt/overview.md) | 40 |

## Inspect this role live

```shell
gcloud iam roles describe roles/saasservicemgmt.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
