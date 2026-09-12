# `roles/anthossupport.serviceAgent`

 Gives the Anthos Support Service Agent access to Cloud Platform resource.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/anthossupport.serviceAgent` |
| Title | Anthos Support Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 36 |
| Service | [anthossupport](../overview.md) |

## Permissions

`roles/anthossupport.serviceAgent` grants 36 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [gkehub](permissions/gkehub/overview.md) | 26 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/anthossupport.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
