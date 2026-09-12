# `roles/opsconfigmonitoring.viewer`

Viewer role for opsconfigmonitoring

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/opsconfigmonitoring.viewer` |
| Title | Opsconfigmonitoring Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 3 |
| Service | [opsconfigmonitoring](../overview.md) |

## Permissions

`roles/opsconfigmonitoring.viewer` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/opsconfigmonitoring.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
