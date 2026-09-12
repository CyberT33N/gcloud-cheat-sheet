# `roles/assuredworkloads.reader`

Grants read access to all Assured Workloads resources and CRM resources - project/folder

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/assuredworkloads.reader` |
| Title | Assured Workloads Reader |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [assuredworkloads](../overview.md) |

## Permissions

`roles/assuredworkloads.reader` grants 19 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [assuredworkloads](permissions/assuredworkloads/overview.md) | 12 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/assuredworkloads.reader --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
