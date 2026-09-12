# `roles/firebase.managementServiceAgent`

Access to create new service agents for Firebase projects; assign roles to service agents; provision GCP resources as required by Firebase services.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/firebase.managementServiceAgent` |
| Title | Firebase Service Management Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 111 |
| Service | [firebase](../overview.md) |

## Permissions

`roles/firebase.managementServiceAgent` grants 111 permissions across 21 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [apikeys](permissions/apikeys/overview.md) | 5 |
| [appengine](permissions/appengine/overview.md) | 5 |
| [bigquery](permissions/bigquery/overview.md) | 7 |
| [clientauthconfig](permissions/clientauthconfig/overview.md) | 10 |
| [datastore](permissions/datastore/overview.md) | 9 |
| [firebase](permissions/firebase/overview.md) | 8 |
| [firebaseabt](permissions/firebaseabt/overview.md) | 1 |
| [firebaseappcheck](permissions/firebaseappcheck/overview.md) | 5 |
| [firebaseapphosting](permissions/firebaseapphosting/overview.md) | 4 |
| [firebaseauth](permissions/firebaseauth/overview.md) | 3 |
| [firebasedataconnect](permissions/firebasedataconnect/overview.md) | 5 |
| [firebasehosting](permissions/firebasehosting/overview.md) | 4 |
| [firebaserules](permissions/firebaserules/overview.md) | 8 |
| [firebasestorage](permissions/firebasestorage/overview.md) | 1 |
| [firebasevertexai](permissions/firebasevertexai/overview.md) | 2 |
| [iam](permissions/iam/overview.md) | 4 |
| [recaptchaenterprise](permissions/recaptchaenterprise/overview.md) | 4 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 5 |
| [servicemanagement](permissions/servicemanagement/overview.md) | 1 |
| [serviceusage](permissions/serviceusage/overview.md) | 12 |
| [storage](permissions/storage/overview.md) | 8 |

## Inspect this role live

```shell
gcloud iam roles describe roles/firebase.managementServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
