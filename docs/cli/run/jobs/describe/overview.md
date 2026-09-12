# run jobs describe

Read the full specification and the live status of one Cloud Run job.

## Usage

```shell
gcloud run jobs describe <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --format=json
```

## Architectural explanation

Returns the complete job resource: the container image, the attached service account, the environment bindings, the labels and under `status.conditions` the readiness evaluation. The `Ready` condition is the platform-side proof that the job is executable (including the image access validation). In PowerShell the JSON form composes with `ConvertFrom-Json` for property-level assertions; the `lastTransitionTime` of the condition proves whether the evaluation is current or stale.

## Verified example

```shell
gcloud run jobs describe dep-intake-fetch --project=test-software-dep-intake --region=europe-west3 --format="json(status.conditions)"
```

A healthy job reports `"status": "True"` on the `Ready` condition with a current `lastTransitionTime`.

## Network form read-back (Direct VPC egress)

```shell
gcloud run jobs describe <JOB_NAME> --project=<PROJECT_ID> --region=<REGION> --format="json(spec.template.metadata.annotations,status.conditions)"
```

The Direct VPC egress attachment of a job surfaces in the gcloud v1 presentation as annotations on the execution template — `run.googleapis.com/network-interfaces` (a JSON string carrying the network and subnetwork resource paths) and `run.googleapis.com/vpc-access-egress` — and NOT as a `vpcAccess` spec field. A projection on `spec.template.spec.template.spec.vpcAccess` therefore returns empty even on an attached job; the annotation projection is the correct proof form.

## Spec projection paths (the ExecutionSpec layering)

The v2 job resource nests the task specification under two template layers with the ExecutionSpec between them: `spec.template.spec.template.spec`. Proven projection paths (proven against the live job resource):

- the container image: `spec.template.spec.template.spec.containers[0].image`
- the execution identity: `spec.template.spec.template.spec.serviceAccountName` (the field is `serviceAccountName`, never `serviceAccount`)

A projection that misses the middle ExecutionSpec layer (for example `spec.template.spec.containers` or a top-level `spec.template.spec.serviceAccount`) resolves nothing and returns empty even on a healthy job.
