# `roles/servicedirectory.networkAttacher`

Gives access to attach VPC Networks to Service Directory Endpoints

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/servicedirectory.networkAttacher` |
| Title | Service Directory Network Attacher |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [servicedirectory](../overview.md) |

## Permissions

`roles/servicedirectory.networkAttacher` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/servicedirectory.networkAttacher --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
