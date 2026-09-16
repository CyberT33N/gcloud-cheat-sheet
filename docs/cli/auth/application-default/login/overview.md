# auth application-default login

Acquire new user credentials for Application Default Credentials (ADC) through an interactive web flow.

## Usage

```shell
gcloud auth application-default login
```

## Architectural explanation

The command obtains user access credentials through a browser-based web flow and stores them in the well-known ADC location, where client libraries and tooling (for example the OpenTofu Google provider and the gcs backend) pick them up for every API call. The flow is interactive by design: it launches a browser (or, with `--no-browser` / `--no-launch-browser`, prints a URL that a human completes on a trusted machine) and therefore always runs in a real interactive terminal — never as a scripted prompt in a non-interactive execution.

An expired or policy-invalidated ADC session surfaces at the first API call as `invalid_grant` with `reauth related error (invalid_rapt)` (the reauthentication policy of the account). The remediation is exactly this interactive login by the user; a scripted credential workaround is never a substitute.

## Verified example

```shell
gcloud auth application-default login
```

Proven result: after the interactive login completed, the previously failing API call path (a Cloud KMS key-data fetch that had failed with `invalid_grant` / `invalid_rapt`) succeeded, and the governed operation depending on it continued.
