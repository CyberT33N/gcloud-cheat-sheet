# `roles/securityposture.admin`

Full access to Security Posture service APIs.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securityposture.admin` |
| Title | Security Posture Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 44 |
| Service | [securityposture](../overview.md) |

## Permissions

`roles/securityposture.admin` grants 44 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [orgpolicy](permissions/orgpolicy/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [securitycenter](permissions/securitycenter/overview.md) | 3 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 7 |
| [securityposture](permissions/securityposture/overview.md) | 21 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securityposture.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
