# organizations add-iam-policy-binding

Bind a member to a role on an organization.

## Usage

```shell
gcloud organizations add-iam-policy-binding <ORGANIZATION_ID> --member="<MEMBER>" --role="<ROLE>"
```

## Architectural explanation

The binding is organization-scoped: the member receives the role on every resource of the organization covered by the role. Organization-policy and access-context-manager administration bind at this level — these roles are not grantable on a project (the bind fails with `INVALID_ARGUMENT: Role <ROLE> is not supported for this resource`; see the troubleshooting entry of [projects add-iam-policy-binding](../../projects/add-iam-policy-binding/overview.md)). For just-in-time administration this is the grant half of the window: grant the minimal phase role, prove it with the read-back, execute the phase, remove it afterwards. The role content is never assumed — it is proven first over `gcloud iam roles describe <ROLE> --format="value(includedPermissions)"`. The mutation's policy echo can be suppressed with the output-mode flag `--format=none`; the independent read-back over [organizations get-iam-policy](../get-iam-policy/overview.md) stays the proof.

## Verified example

```powershell
gcloud organizations add-iam-policy-binding <ORGANIZATION_ID> --member="user:admin@test.software" --role="roles/orgpolicy.policyAdmin" --format=none
$org = gcloud organizations get-iam-policy <ORGANIZATION_ID> --format=json | ConvertFrom-Json
$org.bindings | Where-Object { $_.members -contains 'user:admin@test.software' } | ForEach-Object { $_.role }
```

Proven result during a convergence-window re-grant: `Updated IAM policy for organization [<ORGANIZATION_ID>]`, and the read-back shows the new binding next to the standing `roles/resourcemanager.*` bindings.

Role reference: [`roles/orgpolicy.policyAdmin`](../../../iam/roles/predefined/orgpolicy/policyAdmin/overview.md) — the IAM roles area documents the full permission set of this role.
