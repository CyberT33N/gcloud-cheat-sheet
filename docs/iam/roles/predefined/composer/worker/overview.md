# `roles/composer.worker`

Worker access to Composer. Intended for service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/composer.worker` |
| Title | Composer Worker |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 621 |
| Service | [composer](../overview.md) |

## Permissions

`roles/composer.worker` grants 621 permissions across 18 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 62 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 9 |
| [cloudkms](permissions/cloudkms/overview.md) | 5 |
| [composer](permissions/composer/overview.md) | 1 |
| [compute](permissions/compute/overview.md) | 1 |
| [container](permissions/container/overview.md) | 413 |
| [containeranalysis](permissions/containeranalysis/overview.md) | 5 |
| [datalineage](permissions/datalineage/overview.md) | 10 |
| [logging](permissions/logging/overview.md) | 4 |
| [monitoring](permissions/monitoring/overview.md) | 7 |
| [orgpolicy](permissions/orgpolicy/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 43 |
| [recommender](permissions/recommender/overview.md) | 14 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [source](permissions/source/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 31 |

## Inspect this role live

```shell
gcloud iam roles describe roles/composer.worker --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
