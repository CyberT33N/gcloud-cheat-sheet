# `roles/designcenter.serviceAgent`

Gives the DesignCenter API Service Account access to necessary GCP resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/designcenter.serviceAgent` |
| Title | DesignCenter Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 78 |
| Service | [designcenter](../overview.md) |

## Permissions

`roles/designcenter.serviceAgent` grants 78 permissions across 7 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apphub](permissions/apphub/overview.md) | 20 |
| [cloudbuild](permissions/cloudbuild/overview.md) | 3 |
| [config](permissions/config/overview.md) | 35 |
| [developerconnect](permissions/developerconnect/overview.md) | 3 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 15 |

## Inspect this role live

```shell
gcloud iam roles describe roles/designcenter.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
