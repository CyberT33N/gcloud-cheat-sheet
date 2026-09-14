# kms keys add-iam-policy-binding

Add an IAM policy binding to a key.

## Usage

```shell
gcloud kms keys add-iam-policy-binding <KEY_ID> --keyring=<KEYRING> --location=<LOCATION> --project=<PROJECT_ID> --member="<MEMBER>" --role="<ROLE>" --format=none
```

## Architectural explanation

The resource-sharp grant on a single key — the data-plane half of the two-layer administration form: the project-level management wrapper administers the key lifecycle, while the crypto operations themselves run under a minimal resource-sharp role such as `roles/cloudkms.cryptoKeyEncrypterDecrypter`. The split is forced by the proven role contents: `roles/cloudkms.admin` carries `cloudkms.cryptoKeys.*` but not `cloudkms.cryptoKeyVersions.useToEncrypt/useToDecrypt` (only the `ViaDelegation` variants), so an encrypt/decrypt proof always needs the data-plane grant. The role content is never assumed — it is proven first over `gcloud iam roles describe <ROLE> --format="value(includedPermissions)"`. The mutation's policy echo can be suppressed with `--format=none`; the independent read-back over `get-iam-policy` stays the proof.

## Verified example

```shell
gcloud kms keys add-iam-policy-binding dep-state-encryption --keyring=dep-control --location=europe-west3 --project=test-software-dep-control --member="user:admin@test.software" --role="roles/cloudkms.cryptoKeyEncrypterDecrypter" --format=none
```

Proven result: `Updated IAM policy for key [dep-state-encryption]`, and the read-back shows exactly the member/role binding.
