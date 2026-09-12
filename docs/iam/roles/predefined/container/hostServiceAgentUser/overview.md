# `roles/container.hostServiceAgentUser`

Allows the Kubernetes Engine service account in the host project to configure shared network resources for cluster management. Also gives access to inspect the firewall rules in the host project, and configure Cloud DNS resources.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/container.hostServiceAgentUser` |
| Title | Kubernetes Engine Host Service Agent User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 16 |
| Service | [container](../overview.md) |

## Permissions

`roles/container.hostServiceAgentUser` grants 16 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [compute](permissions/compute/overview.md) | 2 |
| [container](permissions/container/overview.md) | 1 |
| [dns](permissions/dns/overview.md) | 13 |

## Inspect this role live

```shell
gcloud iam roles describe roles/container.hostServiceAgentUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
