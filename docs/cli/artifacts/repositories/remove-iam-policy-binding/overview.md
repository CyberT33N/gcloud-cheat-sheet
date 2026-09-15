# Remove IAM Policy Binding

[INTENT: REFERENCE]

Remove one IAM policy binding (member + role, plus an optional condition) from the IAM policy of an Artifact Registry repository.

```shell
gcloud artifacts repositories remove-iam-policy-binding go-dependencies-evidence --project=test-software-dep-evidence --location=europe-west3 --member="user:<EMAIL>" --role="roles/artifactregistry.writer"
```

## Architecture

- The removal targets exactly one binding: the member and role previously read from the live policy. Read the current policy first with `get-iam-policy` and remove exactly that read form.
- The command is the symmetric counterpart of `add-iam-policy-binding` and shares its precondition: the caller must hold `artifactregistry.repositories.getIamPolicy` and `artifactregistry.repositories.setIamPolicy` on the repository. No data-plane role carries them (proven: the [`roles/artifactregistry.writer`](../../../../iam/roles/predefined/artifactregistry/writer/overview.md) permission list contains neither), so a policy change runs under the minimal carrying role [`roles/artifactregistry.admin`](../../../../iam/roles/predefined/artifactregistry/admin/overview.md), which is removed again right after the proven binding change.
- Prove the removal by an independent read-back (`get-iam-policy`): the target member must be absent from the role's member list and every other binding must be unchanged.

## Troubleshooting

- `PERMISSION_DENIED: Permission 'artifactregistry.repositories.getIamPolicy' denied`: the caller lacks the policy-management capability on the repository. Grant the minimal carrying role for the management step, execute the binding change, prove it by read-back, and remove the management role again.
