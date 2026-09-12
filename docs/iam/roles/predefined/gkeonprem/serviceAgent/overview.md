# `roles/gkeonprem.serviceAgent`

Gives the GKE On-Prem service agent access to Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/gkeonprem.serviceAgent` |
| Title | GKE On-Prem Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 25 |
| Service | [gkeonprem](../overview.md) |

## Permissions

`roles/gkeonprem.serviceAgent` grants 25 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 3 |
| [gkeonprem](permissions/gkeonprem/overview.md) | 22 |

## Inspect this role live

```shell
gcloud iam roles describe roles/gkeonprem.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
