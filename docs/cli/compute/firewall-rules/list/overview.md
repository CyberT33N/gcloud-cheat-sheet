# compute firewall-rules list

List firewall rules, optionally filtered to one network.

## Usage

```shell
gcloud compute firewall-rules list --project=<PROJECT_ID> --filter="network:<NETWORK_NAME>" --format="json(name,direction,priority,destinationRanges,allowed,denied)"
```

## Architectural explanation

The `network:` filter narrows the answer to the rules attached to one VPC, and the JSON projection carries exactly the fields a governed read-back asserts: direction, priority, destination ranges, and the allowed/denied protocols. This is the independent proof half after creating an egress pair.

## Verified example

```shell
gcloud compute firewall-rules list --project=test-software-dep-intake --filter="network:dep-intake-workload" --format="json(name,direction,priority,destinationRanges,allowed,denied)"
```
