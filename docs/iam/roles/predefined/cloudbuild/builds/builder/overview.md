# `roles/cloudbuild.builds.builder`

Can perform builds

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudbuild.builds.builder` |
| Title | Cloud Build Service Account |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 78 |
| Service | [cloudbuild](../../overview.md) |

## Permissions

`roles/cloudbuild.builds.builder` grants 78 permissions across 10 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 45 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 9 |
| [compute](permissions/compute/overview.md) | 1 |
| [containeranalysis](permissions/containeranalysis/overview.md) | 5 |
| [logging](permissions/logging/overview.md) | 3 |
| [pubsub](permissions/pubsub/overview.md) | 2 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [source](permissions/source/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudbuild.builds.builder --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
