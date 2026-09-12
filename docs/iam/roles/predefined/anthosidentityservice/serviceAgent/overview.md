# `roles/anthosidentityservice.serviceAgent`

Gives the Anthos Identity service agent access to Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/anthosidentityservice.serviceAgent` |
| Title | Anthos Identity Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [anthosidentityservice](../overview.md) |

## Permissions

`roles/anthosidentityservice.serviceAgent` grants 11 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/anthosidentityservice.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
