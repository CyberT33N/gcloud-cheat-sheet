# `roles/cloudprofiler.admin`

Admin role for Cloud Profiler

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudprofiler.admin` |
| Title | Cloud Profiler Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 5 |
| Service | [cloudprofiler](../overview.md) |

## Permissions

`roles/cloudprofiler.admin` grants 5 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudprofiler](permissions/cloudprofiler/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudprofiler.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
