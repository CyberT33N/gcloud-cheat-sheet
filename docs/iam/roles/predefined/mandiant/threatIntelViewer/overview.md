# `roles/mandiant.threatIntelViewer`

Access to read Threat Intel

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/mandiant.threatIntelViewer` |
| Title | Mandiant Threat Intel Viewer |
| Type | Predefined role |
| Launch stage | `BETA` |
| Included permissions | 4 |
| Service | [mandiant](../overview.md) |

## Permissions

`roles/mandiant.threatIntelViewer` grants 4 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [mandiant](permissions/mandiant/overview.md) | 2 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/mandiant.threatIntelViewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
