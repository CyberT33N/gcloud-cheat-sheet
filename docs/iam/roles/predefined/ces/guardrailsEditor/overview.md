# `roles/ces.guardrailsEditor`

Full control over safety settings and guardrails.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/ces.guardrailsEditor` |
| Title | Gemini Enterprise for Customer Experience Guardrails Editor |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 121 |
| Service | [ces](../overview.md) |

## Permissions

`roles/ces.guardrailsEditor` grants 121 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [ces](permissions/ces/overview.md) | 43 |
| [contactcenterinsights](permissions/contactcenterinsights/overview.md) | 76 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/ces.guardrailsEditor --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
