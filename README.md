# gcloud-cheat-sheet







# Install

## Ubuntu

Klar. Unter **Ubuntu** würde ich die offizielle APT-Methode von Google verwenden. ([Google Cloud Documentation][1])

### 1. Voraussetzungen installieren

```bash
sudo apt update
sudo apt install -y ca-certificates gnupg curl
```

### 2. Google-Repository-Schlüssel hinzufügen

```bash
curl https://packages.cloud.google.com/apt/doc/apt-key.gpg \
  | sudo gpg --dearmor -o /usr/share/keyrings/cloud.google.gpg
```

### 3. Google-Cloud-Repository hinzufügen

```bash
echo "deb [signed-by=/usr/share/keyrings/cloud.google.gpg] https://packages.cloud.google.com/apt cloud-sdk main" \
  | sudo tee /etc/apt/sources.list.d/google-cloud-sdk.list
```

### 4. `gcloud` installieren

```bash
sudo apt update
sudo apt install -y google-cloud-cli
```

### 5. Installation prüfen

```bash
gcloud version
```

Danach kannst du dich bei Google Cloud anmelden bzw. `gcloud` konfigurieren:

```bash
gcloud init
```

`gcloud init` führt dich durch die Anmeldung und die Auswahl bzw. Einrichtung eines Projekts. ([Google Cloud Documentation][2])

Die offizielle Anleitung findest du hier: [Google Cloud CLI für Ubuntu installieren](https://docs.cloud.google.com/sdk/docs/install-sdk?hl=de&utm_source=chatgpt.com)















<br><br>
<br><br>


<br><br>

## Guides
- https://cloud.google.com/sdk/auth_success





<br><br>
<br><br>

## Files

<br><br>

### copy files to your VM from your local machine.
```shell
gcloud compute scp --project deep-learning-tests-411921 --zone asia-east1-c --recurse <local file or directory> deeplearning-1-vm:~/
```














<br><br>
<br><br>
<br><br>
<br><br>

## SSH

<br><br>

### Create an SSH connection to your machine 
```shell
gcloud compute ssh --project deep-learning-tests-411921 --zone asia-east1-c deeplearning-1-vm
```

<br><br>

### Create an SSH connection to your machine with Port forward
```shell
gcloud compute ssh --project deep-learning-tests-411921 --zone asia-east1-c deeplearning-1-vm -- -L 8080:localhost:8080
```

### Store key with passphrase
- This will save your passphrase that you do not have to enter it again eery time
```shell
eval $(ssh-agent -s)
ssh-add ~/.ssh/dein_private_key
```







<br><br>
<br><br>
__________________________________________________________________________________
__________________________________________________________________________________
<br><br>
<br><br>


## Disk

<br><br>
<br><br>

### Attach snapshot to new vm
1. Create VM
  - You can select the Snapshot in the creation process or go to 2.
2. Shut down VM -> Edit VM -> Remove Boot Disk -> Configure Boot Disk (In my case non fluid default space) -> Snapshots -> Click save




























<br><br>
<br><br>
__________________________________________________________________________________
__________________________________________________________________________________
<br><br>
<br><br>


## Networking

<br><br>

#### Assign a static external IP address to your VM instance
- https://cloud.google.com/compute/docs/instances-and-network?hl=de&_ga=2.160108084.-860786668.1705867154#promote_ephemeral_ip






## Port Forward

<br><br>

### Port Foward Gcloud CLI -> Host-Maschine 
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
- VM_NAME durch den Namen Ihrer VM.
- LOCAL_PORT durch den Port, den Sie auf Ihrer Host-Maschine verwenden möchten.
- REMOTE_PORT durch den Port, der auf Ihrer VM geöffnet ist.

### Terminate Port Forward
```shel
- gcloud compute ssh deeplearning-1-vm --ssh-flag="-L 7865:7865" --terminate
```
