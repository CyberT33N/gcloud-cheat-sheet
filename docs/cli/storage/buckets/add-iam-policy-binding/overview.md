# storage buckets add-iam-policy-binding

Add one IAM policy binding to a Cloud Storage bucket.

## Usage

```shell
gcloud storage buckets add-iam-policy-binding gs://<BUCKET> --member="<MEMBER>" --role="<ROLE>"
```

## Architectural explanation

The binding is bucket-scoped: the member receives the role on exactly this bucket. The command is the resource-sharp grant half of a just-in-time window on a state-bearing bucket — grant the minimal bucket-level role, prove it with the independent read-back over [get-iam-policy](../get-iam-policy/overview.md), execute the phase, and remove it afterwards over [remove-iam-policy-binding](../remove-iam-policy-binding/overview.md).

Grant administration is itself authorized: the caller needs `storage.buckets.setIamPolicy` on the bucket. A caller who lacks it fails fail-closed with `Permission 'storage.buckets.setIamPolicy' denied` — the proven carrier form is a time-boxed project-level administration shell (for example `roles/storage.admin`) on the project that owns the bucket, granted first and removed last. The content of the granted role is never assumed; it is proven first over `gcloud iam roles describe <ROLE> --format="value(includedPermissions)"`. After every IAM change allow a short propagation window (about 60–90 seconds) before the target operation. The mutation's policy echo can be suppressed with the output-mode flag `--format=none`; the independent read-back stays the proof.

`--member` takes the principal form `user|group|serviceAccount:email` or `domain:domain`; `--role` takes the complete predefined role path or a custom role ID. The optional `--condition` / `--condition-from-file` flags attach an IAM condition and are never used for the unconditional window grants.

## Verified example

```powershell
gcloud storage buckets add-iam-policy-binding gs://test-software-foundation-state --member="user:admin@test.software" --role="roles/storage.legacyBucketOwner" --format=none
```

Proven result (the control-zone state-home window): the read-back over [get-iam-policy](../get-iam-policy/overview.md) shows `user:admin@test.software` in the `roles/storage.legacyBucketOwner` member list, and the bucket policy read that was denied before the grant (`storage.buckets.getIamPolicy`) succeeds after the grant and its propagation window.

Role reference: [`roles/storage.legacyBucketOwner`](../../../../iam/roles/predefined/storage/legacyBucketOwner/overview.md) — the IAM roles area documents the full permission set of this role.

## Troubleshooting: bucket-level grant without bucket IAM administration

Granting a bucket-level role fails when the caller lacks `storage.buckets.setIamPolicy` on the bucket, even when the caller already holds bucket data-plane roles such as `roles/storage.objectAdmin`. Verified failure form: `ERROR: (gcloud.storage.buckets.add-iam-policy-binding) ... Permission 'storage.buckets.setIamPolicy' denied on resource ...`. The correction is the two-layer window form: a time-boxed project-level administration shell on the owning project authorizes the grant administration, while the bucket-level role is the actual window grant; the removal runs in the reverse order (bucket grant first, project shell last).
