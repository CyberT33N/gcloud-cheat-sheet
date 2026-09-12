# `roles/compute.networkUser`

Access to use Compute Engine networking resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.networkUser` |
| Title | Compute Network User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 222 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.networkUser` grants 222 permissions across 8 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 102 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 8 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 2 |
| [networksecurity](permissions/networksecurity/overview.md) | 47 |
| [networkservices](permissions/networkservices/overview.md) | 50 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.networkUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
