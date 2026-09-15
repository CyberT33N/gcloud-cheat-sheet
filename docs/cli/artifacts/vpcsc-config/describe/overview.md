# artifacts vpcsc-config describe

Read the VPC Service Controls configuration of Artifact Registry of a project and location.

## Usage

```shell
gcloud artifacts vpcsc-config describe --project=<PROJECT_ID> --location=<LOCATION>
```

## Architectural explanation

The platform creates the zone configuration automatically per location; the describe read is the before-and-after proof of every allowance mutation. An answer carrying only the resource `name` without a `vpcscPolicy` field is the unset default state, which behaves as DENY: remote repositories inside the perimeter then refuse upstream access with `403 Forbidden` at the application layer. After [allow](../allow/overview.md), the read-back must show `vpcscPolicy: ALLOW`. The read requires the get permission on the configuration; without a covering role it fails with `PERMISSION_DENIED` on `artifactregistry.vpcscconfigs.get` — the bound role form is [`roles/artifactregistry.admin`](../../../../iam/roles/predefined/artifactregistry/admin/overview.md) project-scoped (functionally proven; the `includedPermissions` list of the role does not carry the permission).

## Verified example

```shell
gcloud artifacts vpcsc-config describe --project=test-software-dep-intake --location=europe-west3
```
