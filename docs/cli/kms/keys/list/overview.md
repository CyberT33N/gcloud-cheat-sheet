# kms keys list

List the keys within a keyring.

## Usage

```shell
gcloud kms keys list --keyring=<KEYRING> --location=<LOCATION> --project=<PROJECT_ID>
```

## Architectural explanation

Lists every CryptoKey of the keyring with purpose, algorithm, protection level and primary state. This is the baseline read before a key creation: it proves the keyring exists, shows the existing keys, and rules out a name collision. It doubles as the cheap propagation pre-verify after a KMS grant, because it exercises `cloudkms.cryptoKeys.list` through the same permission path the creation will use.

## Verified example

```shell
gcloud kms keys list --keyring=dep-control --location=europe-west3 --project=test-software-dep-control
```

Proven result: one line per key, for example `dep-evidence-signing` with purpose `ASYMMETRIC_SIGN`, algorithm `EC_SIGN_P256_SHA256`, protection level `SOFTWARE`.
