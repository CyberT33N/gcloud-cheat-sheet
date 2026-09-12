# `roles/videostitcher.admin`

Full access to all video stitcher resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/videostitcher.admin` |
| Title | Video Stitcher Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 51 |
| Service | [videostitcher](../overview.md) |

## Permissions

`roles/videostitcher.admin` grants 51 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [videostitcher](permissions/videostitcher/overview.md) | 49 |

## Inspect this role live

```shell
gcloud iam roles describe roles/videostitcher.admin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
