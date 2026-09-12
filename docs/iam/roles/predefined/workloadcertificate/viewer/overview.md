# `roles/workloadcertificate.viewer`

Read-only access to Workload Certificate all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workloadcertificate.viewer` |
| Title | Workload Certificate Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 9 |
| Service | [workloadcertificate](../overview.md) |

## Permissions

`roles/workloadcertificate.viewer` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [workloadcertificate](permissions/workloadcertificate/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workloadcertificate.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
