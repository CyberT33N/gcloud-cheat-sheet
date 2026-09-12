# `roles/compute.networkAdmin`

Full control of Compute Engine networking resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.networkAdmin` |
| Title | Compute Network Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 965 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.networkAdmin` grants 965 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 639 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 39 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 2 |
| [networksecurity](permissions/networksecurity/overview.md) | 125 |
| [networkservices](permissions/networkservices/overview.md) | 132 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 10 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.networkAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
