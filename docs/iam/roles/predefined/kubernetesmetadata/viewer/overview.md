# `roles/kubernetesmetadata.viewer`

Viewer role for kubernetesmetadata

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/kubernetesmetadata.viewer` |
| Title | Kubernetesmetadata Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [kubernetesmetadata](../overview.md) |

## Permissions

`roles/kubernetesmetadata.viewer` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [kubernetesmetadata](permissions/kubernetesmetadata/overview.md) | 1 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/kubernetesmetadata.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
