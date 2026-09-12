# `roles/datastream.viewer`

Read-only access to all Datastream resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/datastream.viewer` |
| Title | Datastream Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 33 |
| Service | [datastream](../overview.md) |

## Permissions

`roles/datastream.viewer` grants 33 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [datastream](permissions/datastream/overview.md) | 31 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/datastream.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
