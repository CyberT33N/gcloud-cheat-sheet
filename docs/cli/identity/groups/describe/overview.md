# identity groups describe

Describe one Cloud Identity group.

## Usage

```shell
gcloud identity groups describe <GROUP_EMAIL>
```

## Architectural explanation

The describe answers the group's identity record (the resource name, display name, description, labels and parent customer). A group that does not exist yields a semantic answer ("There is no such a group associated with the specified argument") with a non-zero exit code — that is the non-existence proof before a creation. The call requires the Cloud Identity API (`cloudidentity.googleapis.com`) enabled on the consumer project and a caller holding the Cloud Identity groups read privilege (for example the Workspace `Groups Admin` role); a disabled API fails with `SERVICE_DISABLED`, a missing privilege with `PERMISSION_DENIED`.

## Verified example

```shell
gcloud identity groups describe dep-forensics-readers@test.software
```
