# identity groups memberships list

List the memberships of a Cloud Identity group.

## Usage

```shell
gcloud identity groups memberships list --group-email="<GROUP_EMAIL>"
```

## Architectural explanation

The list returns every membership with its member key and roles — the read-back that proves exactly the bound membership set (no more, no fewer) after an add or a removal. The call requires the Cloud Identity API and the groups read privilege.

## Verified example

```shell
gcloud identity groups memberships list --group-email="dep-forensics-readers@test.software"
```
