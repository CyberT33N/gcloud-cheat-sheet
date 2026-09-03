# iam roles describe

Describe one IAM role, including its full permission set.

```shell
gcloud iam roles describe roles/run.invoker --format="value(includedPermissions)"
```

Architectural explanation: the `--format="value(includedPermissions)"` projection prints the exact permission list the role grants. This is the mandatory proof before every just-in-time grant — a role is never assumed from its name; its content is read and bound first. Proven examples: `roles/run.invoker` carries `run.jobs.run`; `roles/run.viewer` carries `run.executions.get` and `run.executions.list`; `roles/iam.serviceAccountUser` carries `iam.serviceAccounts.actAs`; `roles/iam.serviceAccountAdmin` carries the service-account lifecycle including `getIamPolicy`/`setIamPolicy`; `roles/artifactregistry.reader` carries `artifactregistry.repositories.downloadArtifacts` (and not `getIamPolicy`); `roles/serviceusage.serviceUsageAdmin` carries `serviceusage.services.enable` and `serviceusage.services.list`.