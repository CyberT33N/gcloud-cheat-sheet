# `roles/notebooks.admin`

Full access to Notebooks all resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/notebooks.admin` |
| Title | Notebooks Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 496 |
| Service | [notebooks](../overview.md) |

## Permissions

`roles/notebooks.admin` grants 496 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 11 |
| [compute](permissions/compute/overview.md) | 412 |
| [notebooks](permissions/notebooks/overview.md) | 61 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/notebooks.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
