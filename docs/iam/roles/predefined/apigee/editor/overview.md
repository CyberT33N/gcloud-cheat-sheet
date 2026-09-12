# `roles/apigee.editor`

Editor role for apigee

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigee.editor` |
| Title | Apigee Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 308 |
| Service | [apigee](../overview.md) |

## Permissions

`roles/apigee.editor` grants 308 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigee](permissions/apigee/overview.md) | 301 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigee.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
