# `roles/anthosservicemesh.serviceAgent`

Gives the Anthos Service Mesh service agent access to Cloud Platform resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/anthosservicemesh.serviceAgent` |
| Title | Anthos Service Mesh Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 230 |
| Service | [anthosservicemesh](../overview.md) |

## Permissions

`roles/anthosservicemesh.serviceAgent` grants 230 permissions across 13 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 43 |
| [container](permissions/container/overview.md) | 75 |
| [gkehub](permissions/gkehub/overview.md) | 11 |
| [logging](permissions/logging/overview.md) | 1 |
| [meshconfig](permissions/meshconfig/overview.md) | 1 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [networksecurity](permissions/networksecurity/overview.md) | 22 |
| [networkservices](permissions/networkservices/overview.md) | 51 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 9 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |
| [workloadcertificate](permissions/workloadcertificate/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/anthosservicemesh.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
