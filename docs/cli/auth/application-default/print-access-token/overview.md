# print-access-token

Print an access token for the current Application Default Credentials.

## Usage

```shell
gcloud auth application-default print-access-token
```

## Architectural explanation

The command is the cheap, non-interactive validity proof of the local ADC: a zero exit code proves that the ADC file exists, is parseable, and holds a refreshable credential; a failure (for example the `invalid_rapt` reauthentication class) proves the ADC must be renewed before any engine or API work. The printed token is a live credential: never log it, never persist it, never paste it into documentation or chat. The proven proof form discards the output and asserts only the exit code.

## Verified example

```powershell
gcloud auth application-default print-access-token | Out-Null; "ADC exit code: $LASTEXITCODE"
```

Verified on Google Cloud SDK 580.0.0 (windows_amd64): the discarded-output form printed `ADC exit code: 0` with a valid ADC, proving validity without exposing the token. The same command fails closed with the `invalid_rapt` class when the ADC is expired; the remediation is the interactive re-login over [login](../login/overview.md), never a scripted workaround.
