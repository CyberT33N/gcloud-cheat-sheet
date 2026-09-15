# storage service-agent

Show or provision the Cloud Storage service agent of a project, and authorize it on a CMEK key.

## Usage

```shell
gcloud storage service-agent --project=<PROJECT_ID> --authorize-cmek=<KMS_KEY_RESOURCE>
```

## Architectural explanation

Displays the Cloud Storage service agent of the project (`service-<PROJECT_NUMBER>@gs-project-accounts.iam.gserviceaccount.com`), provisioning it when absent. With `--authorize-cmek` it grants the service agent the encrypt/decrypt permission on the given Cloud KMS key — the standing functional binding that lets CMEK-protected buckets of the project read and write their objects. This is the only standing grant on a state-home CMEK key; the caller needs the key-level `setIamPolicy` capability (for example a time-boxed [`roles/cloudkms.admin`](../../../iam/roles/predefined/cloudkms/admin/overview.md) window grant). The read-back half is the key's `get-iam-policy`: exactly the service-agent binding.

## Verified example

```shell
gcloud storage service-agent --project=test-software-org-anchor --authorize-cmek=projects/test-software-org-anchor/locations/europe-west3/keyRings/foundation/cryptoKeys/foundation-state-cmek
```

Proven result: `Authorized project test-software-org-anchor to encrypt and decrypt with key ...`, and the key policy read-back shows exactly the `serviceAccount:service-<PROJECT_NUMBER>@gs-project-accounts.iam.gserviceaccount.com` binding with [`roles/cloudkms.cryptoKeyEncrypterDecrypter`](../../../iam/roles/predefined/cloudkms/cryptoKeyEncrypterDecrypter/overview.md) (verified during the foundation state-home key birth).
