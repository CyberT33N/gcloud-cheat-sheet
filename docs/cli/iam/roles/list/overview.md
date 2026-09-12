# iam roles list

List the predefined IAM roles, or the custom roles of an organization or project.

## Usage

```shell
gcloud iam roles list
gcloud iam roles list --organization=<ORGANIZATION_ID>
gcloud iam roles list --project=<PROJECT_ID>
```

## Architectural explanation

Without `--organization` or `--project`, the command lists IAM's predefined roles — the complete Google-managed catalog. With a parent, it lists the custom roles defined for that organization or project. Per role the command returns `name`, `title`, `description`, `stage` and `etag` (the BASIC view of the IAM API); the full permission set of a single role is read through [describe](../describe/overview.md). `--show-deleted` additionally lists deleted custom roles of a parent.

## Verified example

```shell
gcloud iam roles list --limit=3 --format=json
```

Returns the predefined catalog as JSON array with `name`, `title`, `description`, `stage` and `etag` per role. Verified against Google Cloud SDK 580.0.0: the full predefined catalog comprised 2,396 roles on 2026-09-12.

## Complete roles reference

The permission-level reference of every predefined role lives in the IAM roles area: [IAM roles](../../../../iam/roles/overview.md).
