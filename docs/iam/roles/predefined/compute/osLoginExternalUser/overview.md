# `roles/compute.osLoginExternalUser`

Access for an external user to set OS Login information associated with this organization. This role does not grant access to instances. External users must be granted one of the required OS Login IAM roles (https://cloud.google.com/compute/docs/instances/managing-instance-access#configure_users) in order to allow access to instances using SSH.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.osLoginExternalUser` |
| Title | Compute OS Login External User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 1 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.osLoginExternalUser` grants 1 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.osLoginExternalUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
