# `roles/compute.orgSecurityResourceAdmin`

Full control of Compute Engine Firewall Policy associations to the organization or folders.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.orgSecurityResourceAdmin` |
| Title | Compute Organization Resource Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 20 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.orgSecurityResourceAdmin` grants 20 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 8 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.orgSecurityResourceAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
