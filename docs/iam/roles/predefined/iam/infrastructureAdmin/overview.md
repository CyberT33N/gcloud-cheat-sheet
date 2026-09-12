# `roles/iam.infrastructureAdmin`

Enables full control for management of key infrastructure services: GCE, GKE, Storage and Networking

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/iam.infrastructureAdmin` |
| Title | Infrastructure Administrator |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2084 |
| Service | [iam](../overview.md) |

## Permissions

`roles/iam.infrastructureAdmin` grants 2084 permissions across 25 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [backupdr](permissions/backupdr/overview.md) | 21 |
| [cloudaicompanion](permissions/cloudaicompanion/overview.md) | 1 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [cloudnotifications](permissions/cloudnotifications/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 1062 |
| [container](permissions/container/overview.md) | 413 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [logging](permissions/logging/overview.md) | 77 |
| [monitoring](permissions/monitoring/overview.md) | 61 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 39 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 2 |
| [networksecurity](permissions/networksecurity/overview.md) | 125 |
| [networkservices](permissions/networkservices/overview.md) | 132 |
| [observability](permissions/observability/overview.md) | 1 |
| [opsconfigmonitoring](permissions/opsconfigmonitoring/overview.md) | 2 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [recommender](permissions/recommender/overview.md) | 26 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 10 |
| [serviceusage](permissions/serviceusage/overview.md) | 12 |
| [stackdriver](permissions/stackdriver/overview.md) | 4 |
| [storage](permissions/storage/overview.md) | 66 |
| [storagebatchoperations](permissions/storagebatchoperations/overview.md) | 13 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/iam.infrastructureAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
