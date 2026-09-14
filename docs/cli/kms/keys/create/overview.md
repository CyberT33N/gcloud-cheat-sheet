# kms keys create

Create a new key within a keyring.

## Usage

```shell
gcloud kms keys create <KEY_ID> --keyring=<KEYRING> --location=<LOCATION> --project=<PROJECT_ID> --purpose=encryption [--protection-level=hsm] [--rotation-period=90d --next-rotation-time=<RFC3339>] [--destroy-scheduled-duration=120d]
```

## Architectural explanation

Creates a CryptoKey in the given keyring. `--purpose` is always required; for `--purpose=encryption` (ENCRYPT_DECRYPT) the algorithm defaults to `google-symmetric-encryption` (AES-256-GCM) when `--default-algorithm` is omitted. `--protection-level=hsm` creates a hardware-backed key (Cloud HSM, FIPS 140-2 Level 3); the default is `software`. `--rotation-period` (INTEGER[UNIT], units s/m/h/d) and `--next-rotation-time` (RFC3339) define the automatic rotation schedule and must be set together; the rotation period must be at least 24 hours and at most 876,000 hours. `--destroy-scheduled-duration` sets how long key versions remain restorable in the scheduled-for-destruction state; it is immutable after creation and defaults to 30 days.

## Verified example

```powershell
$next = (Get-Date).ToUniversalTime().AddDays(90).ToString("yyyy-MM-ddTHH:mm:ssZ")
gcloud kms keys create dep-state-encryption --keyring=dep-control --location=europe-west3 --project=test-software-dep-control --purpose=encryption --protection-level=hsm --rotation-period=90d --next-rotation-time=$next --destroy-scheduled-duration=120d
```

Proven result on the read-back: the key reports `purpose: ENCRYPT_DECRYPT`, `versionTemplate.algorithm: GOOGLE_SYMMETRIC_ENCRYPTION`, `versionTemplate.protectionLevel: HSM`, `rotationPeriod: 7776000s`, the given `nextRotationTime`, `destroyScheduledDuration: 10368000s` (120 days), and an `ENABLED` primary version.

## Maximum destroy scheduled duration (live-proven bound)

The documentation names only the 30-day default, never a maximum. Proven against the live contract surface: an oversized value is rejected fail-closed before any mutation —

```text
ERROR: (gcloud.kms.keys.create) argument --destroy-scheduled-duration: value must be less than or equal to 120d; received: 315576000000s
```

— so the exact maximum is `120d` (120 days). Because the field is immutable, the probe value on a real key name must be the intended final value: probe above the bound, read the bound from the rejection, then create with the proven bound.
