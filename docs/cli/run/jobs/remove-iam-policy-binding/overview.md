# run jobs remove-iam-policy-binding

Remove one member/role binding from the IAM policy of one Cloud Run job.

## Usage

```shell
gcloud run jobs remove-iam-policy-binding <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --member="serviceAccount:<SERVICE_ACCOUNT_EMAIL>" --role="<ROLE>"
```

## Architectural explanation

The removal targets exactly the member form that was granted. For a role swap the order is add-before-remove: bind the replacement role first, prove it, then remove the old one — the job never loses its invoke capability in between. The read-back over [get-iam-policy](../get-iam-policy/overview.md) proves the policy afterwards.

## Verified example

```shell
gcloud run jobs remove-iam-policy-binding dep-intake-fetch --project=test-software-dep-intake --region=europe-west3 --member="serviceAccount:dep-intake-fetch-trigger@test-software-dep-intake.iam.gserviceaccount.com" --role="roles/run.invoker"
```
