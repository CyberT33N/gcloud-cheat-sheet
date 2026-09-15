# kms keys remove-iam-policy-binding

Remove one IAM policy binding from a key.

## Usage

```shell
gcloud kms keys remove-iam-policy-binding <KEY_ID> --keyring=<KEYRING> --location=<LOCATION> --project=<PROJECT_ID> --member="<MEMBER>" --role="<ROLE>" --format=none
```

## Architectural explanation

Removes exactly the member/role pair that was granted and ends the resource-sharp just-in-time window on the key. The key-level removal runs before the project-level administration wrapper is removed: the wrapper still carries `cloudkms.cryptoKeys.setIamPolicy`, which the removal itself needs. The independent read-back over `get-iam-policy` must show the empty policy afterwards.

## Verified example

```shell
gcloud kms keys remove-iam-policy-binding dep-state-encryption --keyring=dep-control --location=europe-west3 --project=test-software-dep-control --member="user:admin@test.software" --role="roles/cloudkms.cryptoKeyEncrypterDecrypter" --format=none
```

Role reference: [`roles/cloudkms.cryptoKeyEncrypterDecrypter`](../../../../iam/roles/predefined/cloudkms/cryptoKeyEncrypterDecrypter/overview.md) — the IAM roles area documents the full permission set of this role.

Proven result: `Updated IAM policy for key [dep-state-encryption]`, and the read-back shows the empty policy.
