# `roles/datastore.user`

Provides read/write access to data in a Cloud Datastore database. Intended for application developers and service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datastore.user` |
| Title | Cloud Datastore User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 23 |
| Service | [datastore](../overview.md) |

## Permissions

`roles/datastore.user` grants 23 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 6 |
| [datastore](permissions/datastore/overview.md) | 14 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datastore.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
