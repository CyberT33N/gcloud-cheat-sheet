# `roles/securitycenter.securityResponseServiceAgent`

Gives Playbook Runner permissions to execute all Google authored Playbooks. This role will keep evolving as we add more playbooks

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/securitycenter.securityResponseServiceAgent` |
| Title | Google Cloud Security Response Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 11 |
| Service | [securitycenter](../overview.md) |

## Permissions

`roles/securitycenter.securityResponseServiceAgent` grants 11 permissions across 5 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 6 |
| [iam](permissions/iam/overview.md) | 1 |
| [pubsub](permissions/pubsub/overview.md) | 1 |
| [securitycenter](permissions/securitycenter/overview.md) | 1 |
| [storage](permissions/storage/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/securitycenter.securityResponseServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
