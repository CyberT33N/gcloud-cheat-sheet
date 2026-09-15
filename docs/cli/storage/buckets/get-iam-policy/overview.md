# storage buckets get-iam-policy

Get the IAM policy of one Cloud Storage bucket.

## Usage

```shell
gcloud storage buckets get-iam-policy gs://<BUCKET> --format=json
```

## Architectural explanation

The bucket-level authorization read-back: the answer carries the live binding
set, so it proves both the intended grant (for example the resource-sharp
`roles/storage.objectAdmin` operator data plane of a state home) and the
hardened end state after a window (the intended binding removed again). A
newly created bucket additionally carries the platform-default legacy
bindings (`roles/storage.legacyBucketOwner`, `roles/storage.legacyBucketReader`,
`roles/storage.legacyObjectOwner`, `roles/storage.legacyObjectReader` for the
project's owner, editor and viewer principals) — their presence is expected
and is not a window grant. The JSON form composes with `ConvertFrom-Json` in
PowerShell for exact member/role assertions.

## Verified example

```powershell
$policy = gcloud storage buckets get-iam-policy gs://test-software-foundation-state --format=json | ConvertFrom-Json
$policy.bindings | ForEach-Object { "$($_.role): $($_.members -join ',')" }
```

Proven result (the state-home birth window): the binding
`roles/storage.objectAdmin: user:admin@test.software` among the
platform-default legacy bindings.
