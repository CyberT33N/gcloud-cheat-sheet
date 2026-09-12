# `roles/workstations.user`

Grants runtime access to Workstation resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/workstations.user` |
| Title | Cloud Workstations User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [workstations](../overview.md) |

## Permissions

`roles/workstations.user` grants 8 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [workstations](permissions/workstations/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/workstations.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
