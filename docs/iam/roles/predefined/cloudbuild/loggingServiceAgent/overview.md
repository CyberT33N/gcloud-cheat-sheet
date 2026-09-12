# `roles/cloudbuild.loggingServiceAgent`

Gives the Cloud Build logging-specific service account access to write logs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudbuild.loggingServiceAgent` |
| Title | Cloud Build Logging Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [cloudbuild](../overview.md) |

## Permissions

`roles/cloudbuild.loggingServiceAgent` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [logging](permissions/logging/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudbuild.loggingServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
