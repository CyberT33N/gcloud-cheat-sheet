# `roles/rma.runner`

Update and Read access to Rapid Migration Assessment all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/rma.runner` |
| Title | Rapid Migration Assessment Runner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 10 |
| Service | [rma](../overview.md) |

## Permissions

`roles/rma.runner` grants 10 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [rma](permissions/rma/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/rma.runner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
