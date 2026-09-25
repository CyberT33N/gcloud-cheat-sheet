# projects add-iam-policy-binding

Bind a member to a role on a project.

## Usage

```shell
gcloud projects add-iam-policy-binding <PROJECT_ID> --member="<MEMBER>" --role="<ROLE>"
```

## Architectural explanation

The binding is project-scoped: the member receives the role on every resource of the project covered by the role. For just-in-time administration this is the grant half of the window: grant the minimal phase role, prove it with the read-back, execute the phase, remove it afterwards. The role content is never assumed — it is proven first over `gcloud iam roles describe <ROLE> --format="value(includedPermissions)"`. After every IAM change allow a short propagation window (about 60–90 seconds) and pre-verify with a simpler permission proof before the target operation. The mutation's policy echo can be suppressed with the output-mode flag `--format=none`; the independent read-back stays the proof (verified in the controller-activation window).

## Verified example

```shell
gcloud projects add-iam-policy-binding test-software-dep-control --member="user:admin@test.software" --role="roles/run.admin"
```

Role reference: [`roles/run.admin`](../../../iam/roles/predefined/run/admin/overview.md) — the IAM roles area documents the full permission set of this role.

The read-back runs over [get-iam-policy](../get-iam-policy/overview.md); the removal runs over [remove-iam-policy-binding](../remove-iam-policy-binding/overview.md).

## Troubleshooting: role not grantable at project level

Some roles are not grantable on the project resource at all: the bind fails with `INVALID_ARGUMENT: Role <ROLE> is not supported for this resource`. Verified with `roles/orgpolicy.policyAdmin`: organization-policy administration binds above the project — grant the role on the organization (or the owning folder) over [organizations add-iam-policy-binding](../../organizations/overview.md), never on the project. The grant remains a time-boxed window form with the same role-content proof, read-back and removal discipline; only the resource level changes.

## Troubleshooting: conditions are rejected on primitive roles

A binding that combines `--condition` with a primitive (basic) role — `roles/owner`, `roles/editor`, `roles/viewer` — is rejected by the platform: `googleapi: Error 400: LintValidationUnits/BindingRoleAllowConditionCheck Error: Conditions can't be set on primitive roles., badRequest`. The `--condition` flag documentation states the restriction ("`--role` cannot be a basic role"); the live proof was produced from an OpenTofu apply of an equivalent `google_project_iam_member` (the same IAM policy write path). Time-bound or otherwise conditioned bindings require a non-primitive role (predefined or custom); a primitive role can only ever be bound unconditionally.
