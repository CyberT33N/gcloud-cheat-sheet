# `roles/edgecontainer.machineUser`

Access to use Edge Container Machine resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/edgecontainer.machineUser` |
| Title | Edge Container Machine User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 6 |
| Service | [edgecontainer](../overview.md) |

## Permissions

`roles/edgecontainer.machineUser` grants 6 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [edgecontainer](permissions/edgecontainer/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/edgecontainer.machineUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
