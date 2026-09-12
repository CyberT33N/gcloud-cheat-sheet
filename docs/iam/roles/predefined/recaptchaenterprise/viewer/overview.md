# `roles/recaptchaenterprise.viewer`

Access to view reCAPTCHA Enterprise keys and metrics

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/recaptchaenterprise.viewer` |
| Title | reCAPTCHA Enterprise Viewer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 12 |
| Service | [recaptchaenterprise](../overview.md) |

## Permissions

`roles/recaptchaenterprise.viewer` grants 12 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [monitoring](permissions/monitoring/overview.md) | 1 |
| [recaptchaenterprise](permissions/recaptchaenterprise/overview.md) | 9 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/recaptchaenterprise.viewer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
