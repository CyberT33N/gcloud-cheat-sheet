# compute networks create

Create a VPC network; the custom subnet mode creates no automatic subnetworks.

## Usage

```shell
gcloud compute networks create <NETWORK_NAME> --subnet-mode=custom --project=<PROJECT_ID> --description="<DESCRIPTION>"
```

## Architectural explanation

`--subnet-mode=custom` creates the network without automatic subnetworks — the only admissible form for a governed network whose subnetworks are declared individually (an auto-mode network would materialize one undeclared subnetwork per region). The description carries the architectural intent because the network name alone does not document its role. The read-back half is [describe](../describe/overview.md): the proof field is `autoCreateSubnetworks: false`.

## Verified example

```shell
gcloud compute networks create dep-intake-workload --subnet-mode=custom --project=test-software-dep-intake --description="Zone workload network origin: the perimeter-internal network home of the zone workload jobs."
```
