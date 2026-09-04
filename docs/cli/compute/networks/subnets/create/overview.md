# compute networks subnets create

Define a subnetwork for a custom-mode network, optionally with Private Google Access.

## Usage

```shell
gcloud compute networks subnets create <SUBNET_NAME> --network=<NETWORK_NAME> --range=<CIDR> --region=<REGION> --enable-private-ip-google-access --project=<PROJECT_ID> --description="<DESCRIPTION>"
```

## Architectural explanation

Subnetworks are regional resources; the region is part of the subnetwork identity, so the canonical name carries it. `--enable-private-ip-google-access` lets workloads without external IP addresses reach Google APIs through private routing — the required form for a perimeter-internal workload network. The range is an instance-bound value: it is decided and reviewed in the organization instance, never guessed at execution time. The read-back half is [describe](../describe/overview.md): `ipCidrRange` and `privateIpGoogleAccess: true`.

## Verified example

```shell
gcloud compute networks subnets create dep-intake-workload-europe-west3 --network=dep-intake-workload --range=10.62.0.0/26 --region=europe-west3 --enable-private-ip-google-access --project=test-software-dep-intake --description="Zone workload subnetwork with Private Google Access in the job region."
```
