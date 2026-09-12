# `roles/cloudfunctions.serviceAgent`

DEPRECATED: This role is deprecated. Please use roles/cloudfunctions.standardServiceAgent for the Cloud Functions service agent.Gives Cloud Functions service account access to managed resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudfunctions.serviceAgent` |
| Title | (Deprecated) Cloud Functions Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 274 |
| Service | [cloudfunctions](../overview.md) |

## Permissions

`roles/cloudfunctions.serviceAgent` grants 274 permissions across 17 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [artifactregistry](permissions/artifactregistry/overview.md) | 61 |
| [clientauthconfig](permissions/clientauthconfig/overview.md) | 1 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 9 |
| [cloudfunctions](permissions/cloudfunctions/overview.md) | 5 |
| [compute](permissions/compute/overview.md) | 2 |
| [eventarc](permissions/eventarc/overview.md) | 61 |
| [firebasedatabase](permissions/firebasedatabase/overview.md) | 2 |
| [iam](permissions/iam/overview.md) | 4 |
| [pubsub](permissions/pubsub/overview.md) | 14 |
| [recommender](permissions/recommender/overview.md) | 26 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 3 |
| [run](permissions/run/overview.md) | 61 |
| [serviceusage](permissions/serviceusage/overview.md) | 13 |
| [source](permissions/source/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 8 |
| [vpcaccess](permissions/vpcaccess/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudfunctions.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
