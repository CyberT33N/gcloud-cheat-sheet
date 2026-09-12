# `roles/vmwareengine.vmwareenginePrivilegedUser`

Privileged User has access to VMWare Engine Service Privileged API

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/vmwareengine.vmwareenginePrivilegedUser` |
| Title | VMware Engine Service Privileged User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 60 |
| Service | [vmwareengine](../overview.md) |

## Permissions

`roles/vmwareengine.vmwareenginePrivilegedUser` grants 60 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [vmwareengine](permissions/vmwareengine/overview.md) | 58 |

## Inspect this role live

```shell
gcloud iam roles describe roles/vmwareengine.vmwareenginePrivilegedUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
