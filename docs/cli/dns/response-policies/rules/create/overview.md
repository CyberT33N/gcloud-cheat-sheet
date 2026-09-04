# dns response-policies rules create

Create a rule inside a Cloud DNS response policy — including the local-data answer form.

## Usage

```shell
gcloud dns response-policies rules create <RULE_NAME> --response-policy=<POLICY_NAME> --dns-name='<DNS_NAME>' --local-data='name=<DNS_NAME>,type=A,ttl=<TTL>,rrdatas=<IP_1>|<IP_2>' --project=<PROJECT_ID>
```

## Architectural explanation

The rule maps a wildcard or exact DNS name to a local answer. The `--local-data` value is a comma-separated property list; multiple record data values are separated by `|` inside `rrdatas`. In PowerShell the value is passed in single quotes so the wildcard and the separators survive unchanged. For the restricted-range form the rule answers `*.googleapis.com.` with the four `restricted.googleapis.com` A records (`199.36.153.4`–`199.36.153.7`, the published Google VIP range), so every Google API call from the bound network reaches only the VPC Service Controls restricted endpoint. The read-back half is [describe](../describe/overview.md).

## Verified example

```shell
gcloud dns response-policies rules create restricted-googleapis --response-policy=dep-intake-workload-restricted-googleapis --dns-name='*.googleapis.com.' --local-data='name=*.googleapis.com.,type=A,ttl=300,rrdatas=199.36.153.4|199.36.153.5|199.36.153.6|199.36.153.7' --project=test-software-dep-intake
```
