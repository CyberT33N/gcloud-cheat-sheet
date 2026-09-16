# storage buckets remove-iam-policy-binding

Remove one IAM policy binding from a Cloud Storage bucket.

## Usage

```shell
gcloud storage buckets remove-iam-policy-binding gs://<BUCKET> --member="<MEMBER>" --role="<ROLE>"
```

## Architectural explanation

The removal targets exactly the member/role pair that was granted and ends the just-in-time window on the bucket: the hardened end state is a bucket policy without the window binding, proven by the independent read-back over [get-iam-policy](../get-iam-policy/overview.md). The bucket-level removal runs before the project-level administration shell is removed — the shell still carries `storage.buckets.setIamPolicy`, which the removal itself needs. The platform-default legacy bindings of the bucket (the project owner, editor, and viewer principals) are not window grants and are never removed. The optional `--all` flag removes every binding of the role/principal pair irrespective of conditions and is never the window form; the unconditional window binding is removed without any condition flag. The mutation's policy echo can be suppressed with `--format=none`; the independent read-back stays the proof.

## Verified example

```powershell
gcloud storage buckets remove-iam-policy-binding gs://test-software-foundation-state --member="user:admin@test.software" --role="roles/storage.legacyBucketOwner" --format=none
```

Proven result (the control-zone state-home window hardening): the read-back over [get-iam-policy](../get-iam-policy/overview.md) shows the `roles/storage.legacyBucketOwner` member list reduced to the platform-default project principals — the operator member is gone, and the standing data-plane binding (`roles/storage.objectAdmin`) remains untouched.

Role reference: [`roles/storage.legacyBucketOwner`](../../../../iam/roles/predefined/storage/legacyBucketOwner/overview.md) — the IAM roles area documents the full permission set of this role.
