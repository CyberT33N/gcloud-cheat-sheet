# auth list

List the credentialed accounts and the active one.

## Usage

```shell
gcloud auth list
```

## Architectural explanation

The answer shows every credentialed account and marks the active one. This is the preflight proof of every operation: the active account must be the identity the operation is bound to (for example the organization operator), and an operation under a wrong account is caught here before it mutates anything. An expired session surfaces later as `Reauthentication failed. cannot prompt during non-interactive execution` — the remediation is `gcloud auth login` in a real interactive terminal, never a scripted prompt.

## Verified example

```shell
gcloud auth list
```
