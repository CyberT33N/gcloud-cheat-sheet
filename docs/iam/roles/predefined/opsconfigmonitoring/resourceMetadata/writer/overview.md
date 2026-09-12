# `roles/opsconfigmonitoring.resourceMetadata.writer`

Write-only access to resource metadata. This provides exactly the permissions needed by the Ops Config Monitoring metadata agent and other systems that send metadata.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/opsconfigmonitoring.resourceMetadata.writer` |
| Title | Ops Config Monitoring Resource Metadata Writer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 1 |
| Service | [opsconfigmonitoring](../../overview.md) |

## Permissions

`roles/opsconfigmonitoring.resourceMetadata.writer` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/opsconfigmonitoring.resourceMetadata.writer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
