# `roles/assuredworkloads.editor`

Grants read, write access to Assured Workloads resources, CRM resources - project/folder and Organization Policy administration

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/assuredworkloads.editor` |
| Title | Assured Workloads Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 33 |
| Service | [assuredworkloads](../overview.md) |

## Permissions

`roles/assuredworkloads.editor` grants 33 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [assuredworkloads](permissions/assuredworkloads/overview.md) | 17 |
| [axt](permissions/axt/overview.md) | 1 |
| [bigquery](permissions/bigquery/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 1 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/assuredworkloads.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
