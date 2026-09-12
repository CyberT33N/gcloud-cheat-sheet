# `roles/compute.vmExtensionPolicyAdmin`

Administer zone/global VM extension policies.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/compute.vmExtensionPolicyAdmin` |
| Title | Compute VM extension policy admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 19 |
| Service | [compute](../overview.md) |

## Permissions

`roles/compute.vmExtensionPolicyAdmin` grants 19 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 17 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/compute.vmExtensionPolicyAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
