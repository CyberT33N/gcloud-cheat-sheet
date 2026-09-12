# `roles/securesourcemanager.developerConnectLinker`

A Developer Connect Linker can link a Secure Source Manager instance to Developer Connect.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securesourcemanager.developerConnectLinker` |
| Title | Secure Source Manager Developer Connect Linker |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 9 |
| Service | [securesourcemanager](../overview.md) |

## Permissions

`roles/securesourcemanager.developerConnectLinker` grants 9 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |
| [securesourcemanager](permissions/securesourcemanager/overview.md) | 7 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securesourcemanager.developerConnectLinker --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
