# `roles/firebaseappcheck.serviceAgent`

Grants Firebase App Check Service Account access to consumer app attestation resources, such as reCAPTCHA Enterprise and Play Integrity API.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebaseappcheck.serviceAgent` |
| Title | Firebase App Check Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 3 |
| Service | [firebaseappcheck](../overview.md) |

## Permissions

`roles/firebaseappcheck.serviceAgent` grants 3 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [recaptchaenterprise](permissions/recaptchaenterprise/overview.md) | 2 |
| [serviceusage](permissions/serviceusage/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebaseappcheck.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
