# iam roles describe

Describe one IAM role, including its full permission set.

```shell
gcloud iam roles describe roles/run.invoker --format="value(includedPermissions)"
```

Architectural explanation: the `--format="value(includedPermissions)"` projection prints the exact permission list the role grants. This is the mandatory proof before every just-in-time grant — a role is never assumed from its name; its content is read and bound first. Proven examples: [`roles/run.invoker`](../../../../iam/roles/predefined/run/invoker/overview.md) carries `run.jobs.run`; [`roles/run.viewer`](../../../../iam/roles/predefined/run/viewer/overview.md) carries `run.executions.get` and `run.executions.list`; [`roles/iam.serviceAccountUser`](../../../../iam/roles/predefined/iam/serviceAccountUser/overview.md) carries `iam.serviceAccounts.actAs`; [`roles/iam.serviceAccountAdmin`](../../../../iam/roles/predefined/iam/serviceAccountAdmin/overview.md) carries the service-account lifecycle including `getIamPolicy`/`setIamPolicy`; [`roles/artifactregistry.reader`](../../../../iam/roles/predefined/artifactregistry/reader/overview.md) carries `artifactregistry.repositories.downloadArtifacts` (and not `getIamPolicy`); [`roles/serviceusage.serviceUsageAdmin`](../../../../iam/roles/predefined/serviceusage/serviceUsageAdmin/overview.md) carries `serviceusage.services.enable` and `serviceusage.services.list`.