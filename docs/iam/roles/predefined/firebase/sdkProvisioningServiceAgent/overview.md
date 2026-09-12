# `roles/firebase.sdkProvisioningServiceAgent`

Access to provision apps with the Admin SDK.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebase.sdkProvisioningServiceAgent` |
| Title | Firebase SDK Provisioning Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 15 |
| Service | [firebase](../overview.md) |

## Permissions

`roles/firebase.sdkProvisioningServiceAgent` grants 15 permissions across 6 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apikeys](permissions/apikeys/overview.md) | 1 |
| [clientauthconfig](permissions/clientauthconfig/overview.md) | 1 |
| [cloudmessaging](permissions/cloudmessaging/overview.md) | 1 |
| [firebase](permissions/firebase/overview.md) | 1 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 10 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebase.sdkProvisioningServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
