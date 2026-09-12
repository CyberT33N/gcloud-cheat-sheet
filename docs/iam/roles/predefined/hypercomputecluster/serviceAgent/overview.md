# `roles/hypercomputecluster.serviceAgent`

Grants Cluster Director Service Agent access to necessary GCP resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/hypercomputecluster.serviceAgent` |
| Title | Cluster Director Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 254 |
| Service | [hypercomputecluster](../overview.md) |

## Permissions

`roles/hypercomputecluster.serviceAgent` grants 254 permissions across 17 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 3 |
| [cloudquotas](permissions/cloudquotas/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 140 |
| [config](permissions/config/overview.md) | 7 |
| [container](permissions/container/overview.md) | 19 |
| [dns](permissions/dns/overview.md) | 15 |
| [file](permissions/file/overview.md) | 9 |
| [hypercomputecluster](permissions/hypercomputecluster/overview.md) | 11 |
| [iam](permissions/iam/overview.md) | 2 |
| [logging](permissions/logging/overview.md) | 7 |
| [lustre](permissions/lustre/overview.md) | 9 |
| [monitoring](permissions/monitoring/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |
| [servicenetworking](permissions/servicenetworking/overview.md) | 6 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 15 |

## Inspect this role live

```shell
gcloud iam roles describe roles/hypercomputecluster.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
