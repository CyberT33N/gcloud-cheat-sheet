# `roles/osconfig.rolloutServiceAgent`

Grants OS Config Rollout Service Account access to zonal OS Config resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/osconfig.rolloutServiceAgent` |
| Title | Cloud OS Config Rollout Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [osconfig](../overview.md) |

## Permissions

`roles/osconfig.rolloutServiceAgent` grants 4 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [osconfig](permissions/osconfig/overview.md) | 4 |

## Inspect this role live

```shell
gcloud iam roles describe roles/osconfig.rolloutServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
