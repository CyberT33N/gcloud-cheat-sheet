# compute firewall-rules create

Create a VPC firewall rule — including the governed egress allow/deny pair form.

## Usage

Allow form:

```shell
gcloud compute firewall-rules create <RULE_NAME> --network=<NETWORK_NAME> --direction=EGRESS --priority=<PRIORITY> --destination-ranges=<CIDR> --allow=tcp:443 --project=<PROJECT_ID> --description="<DESCRIPTION>"
```

Deny-all form:

```shell
gcloud compute firewall-rules create <RULE_NAME> --network=<NETWORK_NAME> --direction=EGRESS --priority=<PRIORITY> --destination-ranges=0.0.0.0/0 --action=DENY --rules=all --project=<PROJECT_ID> --description="<DESCRIPTION>"
```

## Architectural explanation

Lower priority values win; the governed egress pair orders the allow rule before priority 1000 and the deny-all rule after it, so exactly the declared destination range remains reachable. The deny form uses `--action=DENY` with `--rules=all` instead of `--allow`. Creating firewall rules requires a role carrying `compute.firewalls.create` — `roles/compute.networkAdmin` does NOT carry it (proven via `gcloud iam roles describe`); the minimal canonical role is `roles/compute.securityAdmin`. The read-back half is [list](../list/overview.md) filtered to the network.

## Verified example

```shell
gcloud compute firewall-rules create dep-intake-workload-allow-restricted-googleapis --network=dep-intake-workload --direction=EGRESS --priority=999 --destination-ranges=199.36.153.4/30 --allow=tcp:443 --project=test-software-dep-intake --description="Allow egress TCP 443 to the restricted.googleapis.com VIP range; ordered before priority 1000."
```

```shell
gcloud compute firewall-rules create dep-intake-workload-deny-all-egress --network=dep-intake-workload --direction=EGRESS --priority=1001 --destination-ranges=0.0.0.0/0 --action=DENY --rules=all --project=test-software-dep-intake --description="Deny all remaining egress from the zone workload network; ordered after priority 1000."
```

Note: `199.36.153.4/30` is the published Google `restricted.googleapis.com` VIP range that serves only the VPC Service Controls restricted services.
