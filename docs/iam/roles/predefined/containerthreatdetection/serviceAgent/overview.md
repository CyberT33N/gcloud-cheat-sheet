# `roles/containerthreatdetection.serviceAgent`

Gives Container Threat Detection service account access to enable/disable Container Threat Detection and manage the Container Threat Detection Agent on Google Kubernetes Engine clusters.

## Role details

| Property | Value |
| --- | --- |
| Role ID | `roles/containerthreatdetection.serviceAgent` |
| Title | Container Threat Detection Service Agent |
| Type | Predefined role |
| Launch stage | `GA` |
| Included permissions | 208 |
| Service | [containerthreatdetection](../overview.md) |

## Permissions

`roles/containerthreatdetection.serviceAgent` grants 208 permissions across 3 services. Each service page lists exactly the permissions this role grants on that service and links every permission to its canonical page in the [central permission catalog](../../../../permissions/overview.md).

| Service | Permissions |
| --- | --- |
| [container](permissions/container/overview.md) | 196 |
| [recommender](permissions/recommender/overview.md) | 10 |
| [resourcemanager](permissions/resourcemanager/overview.md) | 2 |

## Inspect this role live

```shell
gcloud iam roles describe roles/containerthreatdetection.serviceAgent --format="value(includedPermissions)"
```

See [iam roles describe](../../../../../cli/iam/roles/describe/overview.md) for the verified command reference.

## Official documentation

- [IAM roles and permissions index](https://cloud.google.com/iam/docs/understanding-roles)
- [Roles overview](https://cloud.google.com/iam/docs/roles-overview)
