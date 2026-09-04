# compute networks describe

Read one VPC network.

## Usage

```shell
gcloud compute networks describe <NETWORK_NAME> --project=<PROJECT_ID> --format="json(name,autoCreateSubnetworks)"
```

## Architectural explanation

The `autoCreateSubnetworks` field is the proof that the network carries the custom subnet mode (`false`) — the declared form in which every subnetwork is created individually. The JSON projection composes with `ConvertFrom-Json` in PowerShell for exact assertions.

## Verified example

```shell
gcloud compute networks describe dep-intake-workload --project=test-software-dep-intake --format="json(name,autoCreateSubnetworks)"
```
