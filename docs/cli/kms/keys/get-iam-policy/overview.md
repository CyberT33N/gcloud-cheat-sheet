# kms keys get-iam-policy

Get the IAM policy of a key.

## Usage

```shell
gcloud kms keys get-iam-policy <KEY_ID> --keyring=<KEYRING> --location=<LOCATION> --project=<PROJECT_ID> --format=json
```

## Architectural explanation

Returns the key-level IAM policy. A key without any binding answers with an empty policy (only `etag` and `version`, no `bindings`) — that empty answer is the hardened-state proof after a just-in-time grant was removed. The JSON form composes with `ConvertFrom-Json` for exact member/role assertions.

## Verified example

```shell
gcloud kms keys get-iam-policy dep-state-encryption --keyring=dep-control --location=europe-west3 --project=test-software-dep-control --format=json
```

Proven result during a just-in-time window: one binding of `user:admin@test.software` with [`roles/cloudkms.cryptoKeyEncrypterDecrypter`](../../../../iam/roles/predefined/cloudkms/cryptoKeyEncrypterDecrypter/overview.md); after the removal the policy answers with no `bindings` at all.
