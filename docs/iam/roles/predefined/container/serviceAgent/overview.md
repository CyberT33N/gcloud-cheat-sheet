# `roles/container.serviceAgent`

Gives Kubernetes Engine account access to manage cluster resources. Includes access to service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/container.serviceAgent` |
| Title | Kubernetes Engine Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1898 |
| Service | [container](../overview.md) |

## Permissions

`roles/container.serviceAgent` grants 1898 permissions across 26 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [autoscaling](permissions/autoscaling/overview.md) | 3 |
| [backupdr](permissions/backupdr/overview.md) | 31 |
| [bigquery](permissions/bigquery/overview.md) | 6 |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 1 |
| [certificatemanager](permissions/certificatemanager/overview.md) | 48 |
| [compute](permissions/compute/overview.md) | 926 |
| [container](permissions/container/overview.md) | 413 |
| [dns](permissions/dns/overview.md) | 45 |
| [file](permissions/file/overview.md) | 37 |
| [iam](permissions/iam/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 1 |
| [lustre](permissions/lustre/overview.md) | 12 |
| [monitoring](permissions/monitoring/overview.md) | 5 |
| [networkconnectivity](permissions/networkconnectivity/overview.md) | 39 |
| [networkmanagement](permissions/networkmanagement/overview.md) | 2 |
| [networksecurity](permissions/networksecurity/overview.md) | 125 |
| [networkservices](permissions/networkservices/overview.md) | 132 |
| [parallelstore](permissions/parallelstore/overview.md) | 12 |
| [pubsub](permissions/pubsub/overview.md) | 3 |
| [recommender](permissions/recommender/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 6 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 4 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 10 |
| [serviceusage](permissions/serviceusage/overview.md) | 11 |
| [tpu](permissions/tpu/overview.md) | 8 |
| [trafficdirector](permissions/trafficdirector/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/container.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
