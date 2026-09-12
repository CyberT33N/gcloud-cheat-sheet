# `roles/appengine.serviceAgent`

Give App Engine Standard Environment service account access to managed resources. Includes access to service accounts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/appengine.serviceAgent` |
| Title | App Engine Standard Environment Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 75 |
| Service | [appengine](../overview.md) |

## Permissions

`roles/appengine.serviceAgent` grants 75 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [appengine](permissions/appengine/overview.md) | 4 |
| [artifactregistry](permissions/artifactregistry/overview.md) | 33 |
| [compute](permissions/compute/overview.md) | 12 |
| [datastore](permissions/datastore/overview.md) | 11 |
| [iam](permissions/iam/overview.md) | 3 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/appengine.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
