# dns response-policies rules describe

Read one rule of a Cloud DNS response policy.

## Usage

```shell
gcloud dns response-policies rules describe <RULE_NAME> --response-policy=<POLICY_NAME> --project=<PROJECT_ID> --format="json(ruleName,dnsName,localData)"
```

## Architectural explanation

The `localData` projection proves the answer the rule returns — for the restricted-range form the four A records of the restricted VIP with their TTL. This is the independent read-back after the rule creation.

## Verified example

```shell
gcloud dns response-policies rules describe restricted-googleapis --response-policy=dep-intake-workload-restricted-googleapis --project=test-software-dep-intake --format="json(ruleName,dnsName,localData)"
```
