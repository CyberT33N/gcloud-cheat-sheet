# compute scp

[INTENT: REFERENCE]

Copy files to and from Compute Engine virtual machine instances.

## Examples

### Copy files to your VM from your local machine

```shell
gcloud compute scp --project deep-learning-tests-411921 --zone asia-east1-c --recurse <local file or directory> deeplearning-1-vm:~/
```

## Flags

| Flag | Description |
|---|---|
| `--compress` | Enable compression. |
| `--dry-run` | Print the equivalent scp/ssh command to stdout instead of executing it. |
| `--force-key-file-overwrite` | Regenerate and overwrite the files of a broken SSH key without asking for confirmation. |
| `--plain` | Suppress the automatic addition of ssh(1)/scp(1) flags. |
| `--port=PORT` | The port to connect to. |
| `--recurse` | Upload directories recursively. |
| `--scp-flag=SCP_FLAG` | Extra flag to be sent to scp. May be repeated. |
| `--ssh-key-file=SSH_KEY_FILE` | Path to the SSH key file. Default: `~/.ssh/google_compute_engine`. |
| `--strict-host-key-checking=MODE` | Override StrictHostKeyChecking behavior. One of: `yes`, `no`, `ask`. |
| `--zone=ZONE` | Zone of the instance to copy files to/from. |
| `--internal-ip` | Connect via internal IP addresses. Mutually exclusive with `--tunnel-through-iap`. |
| `--tunnel-through-iap` | Tunnel the connection through Cloud Identity-Aware Proxy for TCP forwarding. |
| `--network=NETWORK` | VPC network to use when connecting via IP address or FQDN. |
| `--region=REGION` | Region to use when connecting via IP address or FQDN. |
| `--dest-group=DEST_GROUP` | Destination group to use when connecting via IP address or FQDN. |
| `--ssh-key-expiration=TIME` | Time until which the SSH key is valid. Only valid without OS Login. |
| `--ssh-key-expire-after=DURATION` | Maximum time an SSH key is valid once created, e.g. `2m` for 2 minutes. |

gcloud-wide flags: `--access-token-file`, `--account`, `--billing-project`, `--configuration`, `--flags-file`, `--flatten`, `--format`, `--help`, `--impersonate-service-account`, `--log-http`, `--project`, `--quiet`, `--trace-token`, `--user-output-enabled`, `--verbosity`.
