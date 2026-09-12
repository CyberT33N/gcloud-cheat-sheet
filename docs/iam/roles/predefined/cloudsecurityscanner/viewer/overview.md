# `roles/cloudsecurityscanner.viewer`

Read access to all Web Security Scanner resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudsecurityscanner.viewer` |
| Title | Web Security Scanner Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 18 |
| Service | [cloudsecurityscanner](../overview.md) |

## Permissions

`roles/cloudsecurityscanner.viewer` grants 18 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudsecurityscanner](permissions/cloudsecurityscanner/overview.md) | 8 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudsecurityscanner.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
