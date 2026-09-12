# `roles/cloudcontrolspartner.accessApprovalServiceAgent`

Gives the Partner Console service account access to read Access Approval Requests for workloads associated with a partner.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/cloudcontrolspartner.accessApprovalServiceAgent` |
| Title | Cloud Controls Partner Access Approval Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 2 |
| Service | [cloudcontrolspartner](../overview.md) |

## Permissions

`roles/cloudcontrolspartner.accessApprovalServiceAgent` grants 2 permissions across 1 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [accessapproval](permissions/accessapproval/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/cloudcontrolspartner.accessApprovalServiceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
