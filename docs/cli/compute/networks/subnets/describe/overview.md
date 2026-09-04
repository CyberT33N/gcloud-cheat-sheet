# compute networks subnets describe

Read one subnetwork.

## Usage

```shell
gcloud compute networks subnets describe <SUBNET_NAME> --region=<REGION> --project=<PROJECT_ID> --format="json(name,ipCidrRange,privateIpGoogleAccess)"
```

## Architectural explanation

The projection proves the three binding properties of a governed subnetwork in one read: the name, the CIDR range, and the Private Google Access state. The region flag is mandatory because subnetworks are regional resources.

## Verified example

```shell
gcloud compute networks subnets describe dep-intake-workload-europe-west3 --region=europe-west3 --project=test-software-dep-intake --format="json(name,ipCidrRange,privateIpGoogleAccess)"
```
