# dns response-policies create

Create a Cloud DNS response policy bound to one or more networks.

## Usage

```shell
gcloud dns response-policies create <POLICY_NAME> --description="<DESCRIPTION>" --networks=<NETWORK_NAME> --project=<PROJECT_ID>
```

## Architectural explanation

`--description` is a required flag. The `--networks` binding attaches the policy to the VPC whose queries it rewrites — for the restricted-range form this is the zone workload network, so every Google API call from inside resolves according to the policy rules. The read-back half is [describe](../describe/overview.md): the `networks` entry must carry the network URL.

## Verified example

```shell
gcloud dns response-policies create dep-intake-workload-restricted-googleapis --description="Restricted-range DNS form: resolves *.googleapis.com to restricted.googleapis.com inside the zone VPC." --networks=dep-intake-workload --project=test-software-dep-intake
```
