# `roles/apigeeregistry.worker`

The role used by Apigee Registry application workers to read and update Apigee Registry Artifacts.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/apigeeregistry.worker` |
| Title | Cloud Apigee Registry Worker |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 19 |
| Service | [apigeeregistry](../overview.md) |

## Permissions

`roles/apigeeregistry.worker` grants 19 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apigeeregistry](permissions/apigeeregistry/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/apigeeregistry.worker --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
