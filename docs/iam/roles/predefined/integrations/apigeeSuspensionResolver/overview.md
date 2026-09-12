# `roles/integrations.apigeeSuspensionResolver`

A role that can approve / reject Apigee integrations that contain a suspension/wait task.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/integrations.apigeeSuspensionResolver` |
| Title | Apigee Integration Approver |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [integrations](../overview.md) |

## Permissions

`roles/integrations.apigeeSuspensionResolver` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [integrations](permissions/integrations/overview.md) | 6 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/integrations.apigeeSuspensionResolver --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
