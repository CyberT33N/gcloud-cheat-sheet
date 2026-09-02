# compute addresses

[INTENT: REFERENCE]

Manage Compute Engine static IP addresses.

## Assign a static external IP address to your VM instance

Promote an ephemeral external IP address to a static one — official guide: [Promote an ephemeral external IP address](https://cloud.google.com/compute/docs/instances-and-network#promote_ephemeral_ip)

## Create flags

Flags of `gcloud compute addresses create`:

| Flag | Description |
|---|---|
| `--description=DESCRIPTION` | An optional textual description for the addresses. |
| `--endpoint-type=ENDPOINT_TYPE` | Endpoint type of the external IPv6 address. One of: `VM`, `NETLB`. |
| `--network=NETWORK` | Network resource in which the addresses are reserved (global internal addresses). |
| `--network-tier=NETWORK_TIER` | Network tier of the reserved IP addresses. One of: `PREMIUM`, `STANDARD`. Default: `PREMIUM`. |
| `--prefix-length=PREFIX_LENGTH` | Prefix length of the IP range (IPv4: 8–30, IPv6: 96). |
| `--purpose=PURPOSE` | Purpose of the address resource. One of: `VPC_PEERING`, `SHARED_LOADBALANCER_VIP`, `GCE_ENDPOINT`, `IPSEC_INTERCONNECT`, `PRIVATE_SERVICE_CONNECT`. |
| `--subnet=SUBNET` | Subnet name in which the addresses are reserved (internal IP reservation). |
| `--addresses=ADDRESS,...` | Ephemeral IP addresses to promote to reserved status. |
| `--ip-version=IP_VERSION` | IP version to allocate. One of: `IPV4`, `IPV6`. Default: `IPV4`. |
| `--global` | The addresses are global. Mutually exclusive with `--region`. |
| `--region=REGION` | Region of the addresses to create. Mutually exclusive with `--global`. |
| `--internal-range=INTERNAL_RANGE` | Internal range from which to allocate the global internal IP address. |
| `--ip-collection=IP_COLLECTION` | Public delegated prefix (PDP) from which to allocate the BYOIP address. |

gcloud-wide flags: `--access-token-file`, `--account`, `--billing-project`, `--configuration`, `--flags-file`, `--flatten`, `--format`, `--help`, `--impersonate-service-account`, `--log-http`, `--project`, `--quiet`, `--trace-token`, `--user-output-enabled`, `--verbosity`.
