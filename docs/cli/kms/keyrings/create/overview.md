# kms keyrings create

Create a new keyring in a location.

## Usage

```shell
gcloud kms keyrings create <KEYRING> --project=<PROJECT_ID> --location=<LOCATION> --format="value(name)"
```

## Architectural explanation

Creates the keyring that groups the cryptographic keys of one boundary in one location. Keyrings are immutable in name and location after creation — the location couples every contained key and (for the CMEK form) the bucket it protects, so the keyring location is bound at creation and never changed. The command needs `cloudkms.keyRings.create` (for example via a time-boxed [`roles/cloudkms.admin`](../../../../iam/roles/predefined/cloudkms/admin/overview.md) window grant). The read-back half is the keyring list of the location.

## Verified example

```shell
gcloud kms keyrings create foundation --project=test-software-org-anchor --location=europe-west3 --format="value(name)"
```

Proven result: `projects/test-software-org-anchor/locations/europe-west3/keyRings/foundation` (verified during the foundation state-home key birth).
