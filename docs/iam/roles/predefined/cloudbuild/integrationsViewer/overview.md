# `roles/cloudbuild.integrationsViewer`

Can view Integrations

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudbuild.integrationsViewer` |
| Title | Cloud Build Integrations Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 4 |
| Service | [cloudbuild](../overview.md) |

## Permissions

`roles/cloudbuild.integrationsViewer` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudbuild](permissions/cloudbuild/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudbuild.integrationsViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
