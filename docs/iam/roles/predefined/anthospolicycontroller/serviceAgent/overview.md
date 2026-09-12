# `roles/anthospolicycontroller.serviceAgent`

Gives the Anthos Policy Controller service agent access toCloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/anthospolicycontroller.serviceAgent` |
| Title | Anthos Policy Controller Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [anthospolicycontroller](../overview.md) |

## Permissions

`roles/anthospolicycontroller.serviceAgent` grants 11 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 11 |

## Inspect this role live

```shell
gcloud iam roles describe roles/anthospolicycontroller.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
