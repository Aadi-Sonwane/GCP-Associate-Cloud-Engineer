# Compute Vm instace commonds for cloudshell 
## --> VM instance name is :- myvm01
- Creates a new VM instance.
    ```gcp
    gcloud compute instances create 
    ```
- Lists all VM instance in the project.
    ```gcp
    gcloud compute instances list 
    ```
- Describes a specific  VM instance.
    ```gcp
    gcloud compute instances describe myvm01
    ```
- Starts a Stopped VM instance. [ start/stop/restart/delete ]
    ```gcp
    gcloud compute instances start myvm01
    ```
- Adds labels to a specific  VM instance.
    ```gcp
    gcloud compute instances add-labels 
    ```
- Sets the machine type for a VM instance.
    ```gcp
    gcloud compute instances set-machine-type
    ```
- Sets the zone for a VM instance.
    ```gcp
    gcloud compute instances set-zone
    ```
- Sets the disk for a VM instance.
    ```gcp
    gcloud compute instances set-disk
    ```
- Sets the network for a VM instance.
    ```gcp
    gcloud compute instances set-network
    ```
- Sets the firewall rule for a VM instance.
    ```gcp
    gcloud compute instances set-firewall-rules
    ```
