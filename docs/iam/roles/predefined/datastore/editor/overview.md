# `roles/datastore.editor`

Editor role for Cloud Datastore

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datastore.editor` |
| Title | Cloud Datastore Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 45 |
| Service | [datastore](../overview.md) |

## Permissions

`roles/datastore.editor` grants 45 permissions across 4 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [databasesconsole](permissions/databasesconsole/overview.md) | 3 |
| [datastore](permissions/datastore/overview.md) | 39 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datastore.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
