# `roles/cloudbuild.serviceAgent`

Gives Cloud Build service account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudbuild.serviceAgent` |
| Title | Cloud Build Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 132 |
| Service | [cloudbuild](../overview.md) |

## Permissions

`roles/cloudbuild.serviceAgent` grants 132 permissions across 15 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 45 |
| [binaryauthorization](permissions/binaryauthorization/overview.md) | 6 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 14 |
| [compute](permissions/compute/overview.md) | 8 |
| [containeranalysis](permissions/containeranalysis/overview.md) | 11 |
| [developerconnect](permissions/developerconnect/overview.md) | 4 |
| [iam](permissions/iam/overview.md) | 3 |
| [logging](permissions/logging/overview.md) | 6 |
| [pubsub](permissions/pubsub/overview.md) | 8 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [servicedirectory](permissions/servicedirectory/overview.md) | 13 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |
| [source](permissions/source/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudbuild.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
