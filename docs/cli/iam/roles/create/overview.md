# iam roles create

Create a custom role for a project or an organization.

## Usage

```shell
gcloud iam roles create <ROLE_ID> --project=<PROJECT_ID> --title="<TITLE>" --description="<DESCRIPTION>" --permissions=<PERMISSION_1>,<PERMISSION_2> --stage=GA
```

## Architectural explanation

The command births a purpose-bound custom role: the role ID (camel case, never hyphens), exactly one owning surface (`--project` or `--organization`), and the flag-carried content form (`--title`, `--description`, the comma-separated exact permission set `--permissions`, and `--stage` as the lifecycle phase — `GA` for the governed form). The role content is never assumed from a name: the birth is proven by the independent read-back over [describe](../describe/overview.md), which must show exactly the intended permission set. The birth needs `iam.roles.create` on the owning surface — carried by a time-boxed window elevation such as `roles/iam.roleAdmin`, whose content is proven before the grant over [describe](../describe/overview.md) and which is removed after the window. A bucket-level grant of the new role requires the role in the bucket's project or at organization level; the per-project materialization keeps the boundary inside the owning project.

## Verified example

```powershell
gcloud iam roles create stateHomeBucketMetadataRead --project=test-software-dep-control --title="State home bucket metadata read" --description="Read the state bucket resource and its IAM bindings." --permissions="storage.buckets.get,storage.buckets.getIamPolicy" --stage=GA
```

Proven result (the state-home operator metadata-read window): `Created role [stateHomeBucketMetadataRead]`, and the read-back over [describe](../describe/overview.md) shows exactly `storage.buckets.get;storage.buckets.getIamPolicy` with `stage: GA`. The birth echo renders non-ASCII characters of the description through the active console code page (shown as `?` in a dumb-terminal capture); the content proof of the role is the describe read-back, never the echo.
