# config get-value

Read one property of the active gcloud configuration.

## Usage

```shell
gcloud config get-value <PROPERTY>
```

## Architectural explanation

The form `gcloud config get-value project` proves which project a call without an explicit `--project` would target. Every mutation carries its explicit target project, so this read is the preflight that proves the ambient default — a call without an explicit project quota-bills and targets against this default, which is a drift source in multi-project work.

## Verified example

```shell
gcloud config get-value project
```
