# projects remove-iam-policy-binding

Remove one member/role binding from the IAM policy of a project.

## Usage

```shell
gcloud projects remove-iam-policy-binding <PROJECT_ID> --member="<MEMBER>" --role="<ROLE>"
```

## Architectural explanation

The removal targets exactly the member form that was granted and ends the just-in-time window: the hardened end state is a project policy without any standing user binding, proven by the read-back. When a phase also granted service-account-level bindings, remove those first and the project-level administration role last — removing the administration role first strands the service-account-level work behind `PERMISSION_DENIED` on `iam.serviceAccounts.setIamPolicy`.

## Verified example

```shell
gcloud projects remove-iam-policy-binding test-software-dep-control --member="user:admin@test.software" --role="roles/run.admin"
```
