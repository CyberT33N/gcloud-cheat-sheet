# `roles/cloudtpu.serviceAgent`

Give Cloud TPUs service account access to managed resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtpu.serviceAgent` |
| Title | Cloud TPU V2 API Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1273 |
| Service | [cloudtpu](../overview.md) |

## Permissions

`roles/cloudtpu.serviceAgent` grants 1273 permissions across 15 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [compute](permissions/compute/overview.md) | 870 |
| [iam](permissions/iam/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 2 |
| [monitoring](permissions/monitoring/overview.md) | 6 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 39 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 2 |
| [networksecurity](permissions/networksecurity/overview.md) | 125 |
| [networkservices](permissions/networkservices/overview.md) | 132 |
| [pubsub](permissions/pubsub/overview.md) | 45 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 10 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtpu.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
