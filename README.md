# gcloud-cheat-sheet



## gcloud cli cheat

### Guides
- https://cloud.google.com/sdk/auth_success





### copy files to your VM from your local machine.
```
gcloud compute scp --project deep-learning-tests-411921 --zone asia-east1-c --recurse <local file or directory> deeplearning-1-vm:~/
```



### Create an SSH connection to your machine
```
gcloud compute ssh --project deep-learning-tests-411921 --zone asia-east1-c deeplearning-1-vm -- -L 8080:localhost:8080
```



### Assign a static external IP address to your VM instance
- https://cloud.google.com/compute/docs/instances-and-network?hl=de&_ga=2.160108084.-860786668.1705867154#promote_ephemeral_ip



