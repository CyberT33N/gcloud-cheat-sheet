# projects add-iam-policy-binding

Bind a member to a role on a project.

## Usage

```shell
gcloud projects add-iam-policy-binding <PROJECT_ID> --member="<MEMBER>" --role="<ROLE>"
```

## Architectural explanation

The binding is project-scoped: the member receives the role on every resource of the project covered by the role. For just-in-time administration this is the grant half of the window: grant the minimal phase role, prove it with the read-back, execute the phase, remove it afterwards. The role content is never assumed — it is proven first over `gcloud iam roles describe <ROLE> --format="value(includedPermissions)"`. After every IAM change allow a short propagation window (about 60–90 seconds) and pre-verify with a simpler permission proof before the target operation.

## Verified example

```shell
gcloud projects add-iam-policy-binding test-software-dep-control --member="user:admin@test.software" --role="roles/run.admin"
```

The read-back runs over [get-iam-policy](../get-iam-policy/overview.md); the removal runs over [remove-iam-policy-binding](../remove-iam-policy-binding/overview.md).
