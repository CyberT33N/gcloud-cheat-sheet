# `roles/iam.networkAdmin`

Designed for a Network Administrator to manage Network and related GCP resources, create customized monitoring, and viewing configurations

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.networkAdmin` |
| Title | Network Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1688 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.networkAdmin` grants 1688 permissions across 19 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 1062 |
| [dns](permissions/dns/overview.md) | 45 |
| [logging](permissions/logging/overview.md) | 77 |
| [monitoring](permissions/monitoring/overview.md) | 61 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 85 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 36 |
| [networksecurity](permissions/networksecurity/overview.md) | 125 |
| [networkservices](permissions/networkservices/overview.md) | 132 |
| [observability](permissions/observability/overview.md) | 1 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 10 |
| [serviceusage](permissions/serviceusage/overview.md) | 12 |
| [stackdriver](permissions/stackdriver/overview.md) | 4 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.networkAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
