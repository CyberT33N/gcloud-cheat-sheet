# `roles/firebaserules.system`

Read/write/list access for Datastore entities and Cloud Storage objects, as well as get/list/publish access for PubSub topics.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaserules.system` |
| Title | Firebase Rules System |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 17 |
| Service | [firebaserules](../overview.md) |

## Permissions

`roles/firebaserules.system` grants 17 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datastore](permissions/datastore/overview.md) | 7 |
| [pubsub](permissions/pubsub/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 5 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaserules.system --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
