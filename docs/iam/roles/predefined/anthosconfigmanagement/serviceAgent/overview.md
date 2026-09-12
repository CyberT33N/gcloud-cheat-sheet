# `roles/anthosconfigmanagement.serviceAgent`

Gives the Anthos Config Management service agent access toCloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/anthosconfigmanagement.serviceAgent` |
| Title | Anthos Config Management Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [anthosconfigmanagement](../overview.md) |

## Permissions

`roles/anthosconfigmanagement.serviceAgent` grants 12 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [container](permissions/container/overview.md) | 1 |
| [gkehub](permissions/gkehub/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/anthosconfigmanagement.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
