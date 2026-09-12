# `roles/cloudbuild.builds.editor`

Can create and cancel builds

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudbuild.builds.editor` |
| Title | Cloud Build Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [cloudbuild](../../overview.md) |

## Permissions

`roles/cloudbuild.builds.editor` grants 11 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 8 |
| [remotebuildexecution](permissions/remotebuildexecution/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudbuild.builds.editor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
