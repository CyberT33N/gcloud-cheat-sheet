# kms encrypt

Encrypt a plaintext file with a symmetric key.

## Usage

```shell
gcloud kms encrypt --key=<KEY_ID> --keyring=<KEYRING> --location=<LOCATION> --project=<PROJECT_ID> --plaintext-file=<PATH> --ciphertext-file=<PATH>
```

## Architectural explanation

Encrypts a plaintext file (at most 64 KiB) with the primary version of the given key and writes the ciphertext file. The command performs integrity verification on the request and response by default; a governed flow never disables it with `--skip-integrity-verification`. The caller needs `cloudkms.cryptoKeyVersions.useToEncrypt` on the key — for example via a resource-sharp [`roles/cloudkms.cryptoKeyEncrypterDecrypter`](../../../iam/roles/predefined/cloudkms/cryptoKeyEncrypterDecrypter/overview.md) grant; the project-level [`roles/cloudkms.admin`](../../../iam/roles/predefined/cloudkms/admin/overview.md) does not carry it. Together with `decrypt` and a checksum compare this is the functional proof that a freshly created key actually works before anything depends on it.

## Verified example

```shell
gcloud kms encrypt --key=dep-state-encryption --keyring=dep-control --location=europe-west3 --project=test-software-dep-control --plaintext-file=plaintext.txt --ciphertext-file=ciphertext.bin
```

Proven result: exit 0 and the ciphertext file exists; the round-trip proof completes over [decrypt](../decrypt/overview.md) plus a SHA-256 compare of plaintext and decrypted output.
