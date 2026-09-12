# `roles/securityposture.postureEditor`

Mutate and read permissions to the Posture resource.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securityposture.postureEditor` |
| Title | Security Posture Resource Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 7 |
| Service | [securityposture](../overview.md) |

## Permissions

`roles/securityposture.postureEditor` grants 7 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [securityposture](permissions/securityposture/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securityposture.postureEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
