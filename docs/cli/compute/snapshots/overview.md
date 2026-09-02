# compute snapshots

[INTENT: REFERENCE]

Manage Compute Engine snapshots.

## Commands

| Command | Description |
|---|---|
| `add-iam-policy-binding` | Add IAM policy binding to a Compute Engine snapshot. |
| `add-labels` | Add labels to Google Compute Engine snapshots. |
| `create` | Create Compute Engine snapshots. |
| `delete` | Delete Compute Engine snapshots. |
| `describe` | Describe a Compute Engine snapshot. |
| `get-iam-policy` | Get the IAM policy for a Compute Engine snapshot. |
| `list` | List Google Compute Engine snapshots. |
| `remove-iam-policy-binding` | Remove IAM policy binding from a Compute Engine snapshot. |
| `remove-labels` | Remove labels from Google Compute Engine snapshots. |
| `set-iam-policy` | Set the IAM policy for a Compute Engine snapshot. |
| `test-iam-permissions` | Test IAM permissions for a Compute Engine standard or archive snapshot. |
| `update` | Update a Compute Engine snapshot. |
| `update-kms-key` | Update the KMS key of a Compute Engine standard or archive snapshot. |

## Attach a snapshot to a new VM

1. Create the VM — you can select the snapshot during the creation process, or continue with step 2.
2. Shut down the VM → Edit VM → Remove boot disk → Configure boot disk (in my case non-fluid default space) → Snapshots → Click save.
