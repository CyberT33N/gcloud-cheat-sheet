# `roles/cloudtestservice.testAdmin`

Full access to all Test Lab features

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudtestservice.testAdmin` |
| Title | Firebase Test Lab Admin |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 31 |
| Service | [cloudtestservice](../overview.md) |

## Permissions

`roles/cloudtestservice.testAdmin` grants 31 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudtestservice](permissions/cloudtestservice/overview.md) | 4 |
| [cloudtoolresults](permissions/cloudtoolresults/overview.md) | 14 |
| [firebase](permissions/firebase/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [storage](permissions/storage/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudtestservice.testAdmin --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
