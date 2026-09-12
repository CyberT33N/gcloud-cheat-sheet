# `roles/datastore.importExportAdmin`

Full access to manage imports and exports.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datastore.importExportAdmin` |
| Title | Cloud Datastore Import Export Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [datastore](../overview.md) |

## Permissions

`roles/datastore.importExportAdmin` grants 9 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 1 |
| [datastore](permissions/datastore/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datastore.importExportAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
