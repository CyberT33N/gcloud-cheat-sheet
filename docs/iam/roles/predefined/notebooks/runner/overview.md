# `roles/notebooks.runner`

Restricted access for running scheduled Notebooks.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/notebooks.runner` |
| Title | Notebooks Runner |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 462 |
| Service | [notebooks](../overview.md) |

## Permissions

`roles/notebooks.runner` grants 462 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [aiplatform](permissions/aiplatform/overview.md) | 11 |
| [compute](permissions/compute/overview.md) | 412 |
| [notebooks](permissions/notebooks/overview.md) | 27 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/notebooks.runner --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
