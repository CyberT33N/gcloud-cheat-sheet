# artifacts vpcsc-config allow

Allow the configured upstream sources of the remote repositories of a project and location inside a VPC Service Controls perimeter.

## Usage

```shell
gcloud artifacts vpcsc-config allow --project=<PROJECT_ID> --location=<LOCATION>
```

## Architectural explanation

Inside an enforced VPC Service Controls perimeter, Artifact Registry denies the upstream access of remote repositories by default: an unset VPCSC configuration carries the DENY default, and a remote repository fetch then fails with `403 Forbidden` at the application layer — not a perimeter denial (no `vpcServiceControlsUniqueIdentifier` marker, no `code=7` audit entry) and not an auditable IAM denial. The `allow` mutation sets the zone- and location-sharp configuration to `vpcscPolicy: ALLOW`. The allowance covers only the configured upstreams of the remote repositories in exactly this project and location; it is never a perimeter egress policy — the perimeter form stays unchanged. The operation requires the update permission on the VPCSC configuration; the bound role form is [`roles/artifactregistry.admin`](../../../../iam/roles/predefined/artifactregistry/admin/overview.md) project-scoped, proven functionally (the `includedPermissions` list of the role does not carry the `vpcscconfigs` permissions — when the list read and the documentation statement diverge, the functional grant test is the decisive proof form: grant, prove, execute, remove, prove). The command output already carries the resulting state; the independent proof is the [describe](../describe/overview.md) read-back showing `vpcscPolicy: ALLOW`. The rollback form is `gcloud artifacts vpcsc-config deny --project=<PROJECT_ID> --location=<LOCATION>`.

## Verified example

```shell
gcloud artifacts vpcsc-config allow --project=test-software-dep-intake --location=europe-west3
```
