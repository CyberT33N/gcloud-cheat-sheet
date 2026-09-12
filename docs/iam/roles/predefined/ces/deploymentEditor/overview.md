# `roles/ces.deploymentEditor`

Ability to manage deployments and configure specific app versions.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ces.deploymentEditor` |
| Title | Gemini Enterprise for Customer Experience Deployment Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 118 |
| Service | [ces](../overview.md) |

## Permissions

`roles/ces.deploymentEditor` grants 118 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [ces](permissions/ces/overview.md) | 40 |
| [contactcenterinsights](permissions/contactcenterinsights/overview.md) | 76 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ces.deploymentEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
