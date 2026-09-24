# organizations remove-iam-policy-binding

Remove one member/role binding from the IAM policy of an organization.

## Usage

```shell
gcloud organizations remove-iam-policy-binding <ORGANIZATION_ID> --member="<MEMBER>" --role="<ROLE>"
```

## Architectural explanation

The removal targets exactly the member form that was granted at the organization level and ends the just-in-time window there: the hardened end state is an organization policy that carries only the standing roles of the operator, proven by the read-back. The mutation's policy echo can be suppressed with the output-mode flag `--format=none`; the independent read-back over `organizations get-iam-policy` stays the proof. The removal of org-level window roles never strands the mutation channel itself: the standing `roles/resourcemanager.organizationAdmin` binding carries the org-policy mutation capability, so the window roles can be removed in any order and the read-back keeps working with only the standing roles left.

## Verified example

```powershell
gcloud organizations remove-iam-policy-binding <ORGANIZATION_ID> --member="user:admin@test.software" --role="roles/orgpolicy.policyAdmin" --format=none
$org = gcloud organizations get-iam-policy <ORGANIZATION_ID> --format=json | ConvertFrom-Json
$org.bindings | Where-Object { $_.members -contains 'user:admin@test.software' } | ForEach-Object { $_.role }
```

Proven result during a hardening window: `Updated IAM policy for organization [<ORGANIZATION_ID>]`, and the read-back shows the removed role absent while the standing `roles/resourcemanager.*` bindings remain.

Role reference: [`roles/orgpolicy.policyAdmin`](../../../iam/roles/predefined/orgpolicy/policyAdmin/overview.md) — the IAM roles area documents the full permission set of this role.
