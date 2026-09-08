# identity groups create

Create a new Cloud Identity group.

## Usage

```shell
gcloud identity groups create <GROUP_EMAIL> --organization="<ORGANIZATION_DOMAIN>" --group-type="security" --display-name="<NAME>" --description="<DESCRIPTION>" --with-initial-owner=empty
```

## Architectural explanation

The creation binds the group's email, type, display name and description. `--group-type="security"` marks the IAM-bound access-control class (not a discussion forum). `--with-initial-owner=empty` keeps the creator out of the owner role when the binding declares a plain initial member — the default for a non-dynamic group would make the creator the initial owner. The call requires the Cloud Identity API enabled on the consumer project AND the Cloud Identity groups admin privilege (the Workspace `Groups Admin` role, assigned in the Admin console — a separate plane from GCP IAM); a missing privilege fails with `PERMISSION_DENIED: Error(2015)`. The read-back half is [describe](../describe/overview.md).

## Verified example

```shell
gcloud identity groups create dep-forensics-readers@test.software --organization="test.software" --group-type="security" --display-name="dep-forensics-readers" --description="<DESCRIPTION>" --with-initial-owner=empty
```
