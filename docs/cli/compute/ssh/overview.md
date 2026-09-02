# compute ssh

[INTENT: REFERENCE]

SSH into Compute Engine virtual machine instances.

## Examples

### Create an SSH connection to your machine

```shell
gcloud compute ssh --project deep-learning-tests-411921 --zone asia-east1-c deeplearning-1-vm
```

### Store key with passphrase

This saves your passphrase so that you do not have to enter it again every time:

```shell
eval $(ssh-agent -s)
ssh-add ~/.ssh/your_private_key
```

## Flags

| Flag | Description |
|---|---|
| `--command=COMMAND` | A command to run on the virtual machine; runs and then exits. |
| `--container=CONTAINER` | Name or ID of a container inside the VM (Container-Optimized images only). |
| `--dry-run` | Print the equivalent scp/ssh command to stdout instead of executing it. |
| `--force-key-file-overwrite` | Regenerate and overwrite the files of a broken SSH key without asking for confirmation. |
| `--plain` | Suppress the automatic addition of ssh(1)/scp(1) flags. |
| `--ssh-flag=SSH_FLAG` | Additional flag passed to ssh(1). May be repeated. Supports `%USER%`, `%INSTANCE%`, `%INTERNAL%` substitution. |
| `--ssh-key-file=SSH_KEY_FILE` | Path to the SSH key file. Default: `~/.ssh/google_compute_engine`. |
| `--strict-host-key-checking=MODE` | Override StrictHostKeyChecking behavior. One of: `yes`, `no`, `ask`. |
| `--troubleshoot` | Investigate SSH connection problems (VM status, network, permissions, VPC, boot). |
| `--zone=ZONE` | Zone of the instance to connect to. |
| `--internal-ip` | Connect via internal IP addresses. Mutually exclusive with `--tunnel-through-iap`. |
| `--tunnel-through-iap` | Tunnel the connection through Cloud Identity-Aware Proxy for TCP forwarding. |
| `--network=NETWORK` | VPC network to use when connecting via IP address or FQDN. |
| `--region=REGION` | Region to use when connecting via IP address or FQDN. |
| `--dest-group=DEST_GROUP` | Destination group to use when connecting via IP address or FQDN. |
| `--ssh-key-expiration=TIME` | Time until which the SSH key is valid. Only valid without OS Login. |
| `--ssh-key-expire-after=DURATION` | Maximum time an SSH key is valid once created, e.g. `2m` for 2 minutes. |

gcloud-wide flags: `--access-token-file`, `--account`, `--billing-project`, `--configuration`, `--flags-file`, `--flatten`, `--format`, `--help`, `--impersonate-service-account`, `--log-http`, `--project`, `--quiet`, `--trace-token`, `--user-output-enabled`, `--verbosity`.

## Related

- [Port forwarding](port-forwarding.md) — SSH port forwarding from the gcloud CLI to the host machine
