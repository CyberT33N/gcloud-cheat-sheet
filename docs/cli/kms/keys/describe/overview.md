# kms keys describe

Get the metadata of one key, including its primary version.

## Usage

```shell
gcloud kms keys describe <KEY_ID> --keyring=<KEYRING> --location=<LOCATION> --project=<PROJECT_ID> --format=json
```

## Architectural explanation

Returns the CryptoKey resource: `purpose`, `versionTemplate` (the algorithm and protection level every new version inherits), `rotationPeriod`/`nextRotationTime`, `destroyScheduledDuration`, and the `primary` version with its `state`. The JSON form composes with `ConvertFrom-Json` for property-level assertions — this is the independent read-back half of every key creation.

## Verified example

```shell
gcloud kms keys describe dep-state-encryption --keyring=dep-control --location=europe-west3 --project=test-software-dep-control --format=json
```

Proven result: a key created in the dual-fortress form reports `purpose: ENCRYPT_DECRYPT`, `versionTemplate.algorithm: GOOGLE_SYMMETRIC_ENCRYPTION`, `versionTemplate.protectionLevel: HSM`, `rotationPeriod: 7776000s`, `destroyScheduledDuration: 10368000s`, and `primary.state: ENABLED`.
