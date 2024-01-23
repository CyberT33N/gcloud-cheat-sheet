# gcloud-cheat-sheet


<br><br>
<br><br>

## CLI cheat

<br><br>

### Guides
- https://cloud.google.com/sdk/auth_success





<br><br>
<br><br>

### Files

<br><br>

#### copy files to your VM from your local machine.
```shell
gcloud compute scp --project deep-learning-tests-411921 --zone asia-east1-c --recurse <local file or directory> deeplearning-1-vm:~/
```



### SSH

<br><br>

#### Create an SSH connection to your machine 
```shell
gcloud compute ssh --project deep-learning-tests-411921 --zone asia-east1-c deeplearning-1-vm
```

<br><br>

#### Create an SSH connection to your machine with Port forward
```shell
gcloud compute ssh --project deep-learning-tests-411921 --zone asia-east1-c deeplearning-1-vm -- -L 8080:localhost:8080
```



### Networking

<br><br>

#### Assign a static external IP address to your VM instance
- https://cloud.google.com/compute/docs/instances-and-network?hl=de&_ga=2.160108084.-860786668.1705867154#promote_ephemeral_ip






### Port Forward

<br><br>

#### Port Foward Gcloud CLI -> Host-Maschine 
```shell
# Option 1
gcloud compute ssh deeplearning-1-vm --ssh-flag="-L 7865:7865"

# Option 2
gcloud compute ssh --ssh-flag="-L 4000:localhost:7865"  --zone "asia-east1-c" "deeplearning-1-vm"

# Option 3
gcloud compute ssh deeplearning-1-vm --zone=asia-east1-c -- -NL 4001:localhost:7865
```
- VM_NAME durch den Namen Ihrer VM.
- LOCAL_PORT durch den Port, den Sie auf Ihrer Host-Maschine verwenden möchten.
- REMOTE_PORT durch den Port, der auf Ihrer VM geöffnet ist.

#### Terminate Port Forward
```shel
- gcloud compute ssh deeplearning-1-vm --ssh-flag="-L 7865:7865" --terminate
```
