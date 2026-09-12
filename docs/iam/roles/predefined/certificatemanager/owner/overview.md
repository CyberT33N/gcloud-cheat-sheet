# `roles/certificatemanager.owner`

Full access to Certificate Manager all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/certificatemanager.owner` |
| Title | Certificate Manager Owner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 69 |
| Service | [certificatemanager](../overview.md) |

## Permissions

`roles/certificatemanager.owner` grants 69 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [certificatemanager](permissions/certificatemanager/overview.md) | 67 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/certificatemanager.owner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
