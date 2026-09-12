# `roles/firebasedataconnect.serviceAgent`

Gives Firebase Data Connect access to administer Cloud SQL instances.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebasedataconnect.serviceAgent` |
| Title | Firebase Data Connect Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [firebasedataconnect](../overview.md) |

## Permissions

`roles/firebasedataconnect.serviceAgent` grants 11 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudsql](permissions/cloudsql/overview.md) | 9 |
| [run](permissions/run/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebasedataconnect.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
