# `roles/baremetalsolution.serviceAgent`

Gives permission to manage network resources such as interconnect pairing keys, required for Bare Metal Solution.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/baremetalsolution.serviceAgent` |
| Title | Bare Metal Solution Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [baremetalsolution](../overview.md) |

## Permissions

`roles/baremetalsolution.serviceAgent` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/baremetalsolution.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
