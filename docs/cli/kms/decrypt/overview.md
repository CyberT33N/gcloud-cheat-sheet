# kms decrypt

Decrypt a ciphertext file with a symmetric key.

## Usage

```shell
gcloud kms decrypt --key=<KEY_ID> --keyring=<KEYRING> --location=<LOCATION> --project=<PROJECT_ID> --ciphertext-file=<PATH> --plaintext-file=<PATH>
```

## Architectural explanation

Decrypts a ciphertext file produced by `gcloud kms encrypt`. For symmetric keys the key version is detected from the ciphertext — never pass a version to a symmetric decryption request. The caller needs `cloudkms.cryptoKeyVersions.useToDecrypt` on the key ([`roles/cloudkms.cryptoKeyDecrypter`](../../../iam/roles/predefined/cloudkms/cryptoKeyDecrypter/overview.md) or [`roles/cloudkms.cryptoKeyEncrypterDecrypter`](../../../iam/roles/predefined/cloudkms/cryptoKeyEncrypterDecrypter/overview.md)). Integrity verification is active by default.

## Verified example

```shell
gcloud kms decrypt --key=dep-state-encryption --keyring=dep-control --location=europe-west3 --project=test-software-dep-control --ciphertext-file=ciphertext.bin --plaintext-file=plaintext.dec.txt
```

Proven result: exit 0, and the decrypted file is byte-identical to the original plaintext (SHA-256 compare of both files).
