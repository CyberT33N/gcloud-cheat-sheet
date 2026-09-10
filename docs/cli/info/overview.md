# info

Read the local gcloud installation and configuration metadata.

## Usage

```shell
gcloud info --format="value(<PROPERTY>)"
```

## Architectural explanation

The form is a local, read-only introspection: it reports the SDK installation and the active configuration from the local installation, without any platform call, any credential use, or any mutation. The `installation.sdk_root` property proves the SDK installation root — the preflight for reading the bundled surface implementations as the ground truth of a command's wire form when the platform behavior of a documented command must be proven against the tool that executes it. Every value read this way is installation metadata, never a credential.

## Verified example

```shell
gcloud info --format="value(installation.sdk_root)"
```

returns the SDK installation root of the local installation (for example `C:\Users\<USER>\AppData\Local\Google\Cloud SDK\google-cloud-sdk`).
