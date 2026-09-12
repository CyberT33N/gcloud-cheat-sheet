# `roles/cloudtrace.user`

User access to Cloud Trace. Can view traces, insights and stats. Can create, list, view, and delete tasks.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtrace.user` |
| Title | Cloud Trace User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 22 |
| Service | [cloudtrace](../overview.md) |

## Permissions

`roles/cloudtrace.user` grants 22 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtrace](permissions/cloudtrace/overview.md) | 14 |
| [observability](permissions/observability/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtrace.user --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
