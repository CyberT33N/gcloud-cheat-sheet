# `roles/healthcare.hl7V2Consumer`

List and read HL7v2 messages, update message labels, and publish new messages.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/healthcare.hl7V2Consumer` |
| Title | Healthcare HL7v2 Message Consumer |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 13 |
| Service | [healthcare](../overview.md) |

## Permissions

`roles/healthcare.hl7V2Consumer` grants 13 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [healthcare](permissions/healthcare/overview.md) | 11 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/healthcare.hl7V2Consumer --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
