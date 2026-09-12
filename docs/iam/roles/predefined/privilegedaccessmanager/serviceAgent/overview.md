# `roles/privilegedaccessmanager.serviceAgent`

Gives privileged access manager service account access to modify IAM policies on GCP resources

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/privilegedaccessmanager.serviceAgent` |
| Title | Privileged Access Manager Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [privilegedaccessmanager](../overview.md) |

## Permissions

`roles/privilegedaccessmanager.serviceAgent` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [iam](permissions/iam/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 9 |

## Inspect this role live

```shell
gcloud iam roles describe roles/privilegedaccessmanager.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
