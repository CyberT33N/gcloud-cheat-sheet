# storage buckets describe

Describe one Cloud Storage bucket with its full configuration surface.

## Usage

```shell
gcloud storage buckets describe gs://<BUCKET> --format=json
```

## Architectural explanation

The independent read-back of a born or modified bucket: the answer carries the
live configuration, never the declared one, so it is the proof half of every
bucket provisioning. The `--format=json` form emits the standardized document
with snake_case keys; the fields that carry the dual-fortress state-home form
are `name`, `location` (reported uppercase), `uniform_bucket_level_access`,
`public_access_prevention`, `versioning_enabled` and `default_kms_key` (the
full CMEK key resource name). A `soft_delete_policy` with a
`retentionDurationSeconds` is the platform default on every new bucket, not a
declared lifecycle rule — a declared age-based deletion would surface as a
`lifecycle` block, and a state home never carries one. The sibling inline form
on the group page projects the same fields through `--format="value(...)"`.

## Verified example

```powershell
gcloud storage buckets describe gs://test-software-foundation-state --format=json
```

Proven result (the state-home birth window): `name` =
`test-software-foundation-state`, `location` = `EUROPE-WEST3`,
`uniform_bucket_level_access` = `true`, `public_access_prevention` =
`"enforced"`, `versioning_enabled` = `true`, `default_kms_key` = the bound
CMEK key resource name, and no `lifecycle` block.
