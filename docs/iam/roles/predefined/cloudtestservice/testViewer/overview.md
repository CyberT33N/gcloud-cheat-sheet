# `roles/cloudtestservice.testViewer`

Read access to Test Lab features

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtestservice.testViewer` |
| Title | Firebase Test Lab Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [cloudtestservice](../overview.md) |

## Permissions

`roles/cloudtestservice.testViewer` grants 16 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtestservice](permissions/cloudtestservice/overview.md) | 2 |
| [cloudtoolresults](permissions/cloudtoolresults/overview.md) | 7 |
| [firebase](permissions/firebase/overview.md) | 3 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtestservice.testViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
