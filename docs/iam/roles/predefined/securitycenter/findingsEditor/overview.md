# `roles/securitycenter.findingsEditor`

Read-write access to findings

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.findingsEditor` |
| Title | Security Center Findings Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 27 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.findingsEditor` grants 27 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [securitycenter](permissions/securitycenter/overview.md) | 24 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.findingsEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
