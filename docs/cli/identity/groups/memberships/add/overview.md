# identity groups memberships add

Add a member to an existing Cloud Identity group.

## Usage

```shell
gcloud identity groups memberships add --group-email="<GROUP_EMAIL>" --member-email="<MEMBER_EMAIL>"
```

## Architectural explanation

The add creates one membership. `--roles` defaults to `MEMBER` — the plain membership form; `OWNER` or `MANAGER` are added only when the binding declares them. Omit `--expiration` for a standing membership (an expiration makes it time-boxed). The call requires the Cloud Identity API and the groups admin privilege. The read-back half is [list](../list/overview.md).

## Verified example

```shell
gcloud identity groups memberships add --group-email="dep-forensics-readers@test.software" --member-email="admin@test.software"
```
