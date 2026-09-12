# `roles/chronicle.orgServiceAgent`

Gives Secops Service Agent access to organization level resources like CAI.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/chronicle.orgServiceAgent` |
| Title | Chronicle Organization Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [chronicle](../overview.md) |

## Permissions

`roles/chronicle.orgServiceAgent` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudasset](permissions/cloudasset/overview.md) | 7 |
| [iam](permissions/iam/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/chronicle.orgServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
