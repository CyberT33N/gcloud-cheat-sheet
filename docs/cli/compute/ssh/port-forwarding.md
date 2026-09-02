# compute ssh — Port forwarding

[INTENT: REFERENCE]

## Create an SSH connection to your machine with port forward

```shell
gcloud compute ssh --project deep-learning-tests-411921 --zone asia-east1-c deeplearning-1-vm -- -L 8080:localhost:8080
```

## Port forward gcloud CLI to host machine

```shell
# Option 1
gcloud compute ssh --project deep-learning-tests-411921 --zone us-central1-b deeplearning-1-vm -- -L 9090:localhost:9090

# Option 2
gcloud compute ssh deeplearning-1-vm --ssh-flag="-L 7865:7865"

# Option 3
gcloud compute ssh --ssh-flag="-L 4000:localhost:7865"  --zone "asia-east1-c" "deeplearning-1-vm"

# Option 4
gcloud compute ssh deeplearning-1-vm --zone=asia-east1-c -- -NL 4001:localhost:7865
```

Replace:

- `VM_NAME` with the name of your VM.
- `LOCAL_PORT` with the port you want to use on your host machine.
- `REMOTE_PORT` with the port that is open on your VM.

## Terminate port forward

```shell
gcloud compute ssh deeplearning-1-vm --ssh-flag="-L 7865:7865" --terminate
```
