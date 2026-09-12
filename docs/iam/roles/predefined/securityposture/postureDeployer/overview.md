# `roles/securityposture.postureDeployer`

Mutate and read permissions to the Posture Deployment resource.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securityposture.postureDeployer` |
| Title | Security Posture Deployer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 25 |
| Service | [securityposture](../overview.md) |

## Permissions

`roles/securityposture.postureDeployer` grants 25 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [orgpolicy](permissions/orgpolicy/overview.md) | 12 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [securitycenter](permissions/securitycenter/overview.md) | 3 |
| [securitycentermanagement](permissions/securitycentermanagement/overview.md) | 3 |
| [securityposture](permissions/securityposture/overview.md) | 6 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securityposture.postureDeployer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
