# `roles/securitycenter.automationServiceAgent`

Security Center automation service agent can configure GCP resources to enable security scanning.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.automationServiceAgent` |
| Title | Security Center Automation Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 21 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.automationServiceAgent` grants 21 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 6 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.automationServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
