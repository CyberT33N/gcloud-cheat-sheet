# `roles/container.cloudKmsKeyUser`

Allow the Kubernetes Engine service agent in the cluster project to call KMS with user provided crypto keys to sign payloads.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/container.cloudKmsKeyUser` |
| Title | Kubernetes Engine KMS Crypto Key User |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 8 |
| Service | [container](../overview.md) |

## Permissions

`roles/container.cloudKmsKeyUser` grants 8 permissions across 2 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [cloudkms](permissions/cloudkms/overview.md) | 7 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 1 |

## Inspect this role live

```shell
gcloud iam roles describe roles/container.cloudKmsKeyUser --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
