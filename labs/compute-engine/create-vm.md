# 🧪 Lab: Create a VM Instance on Google Compute Engine

This hands-on lab demonstrates how to create a virtual machine (VM) in Google Cloud using Compute Engine.

## 🎯 Objective

By the end of this lab, you will be able to:
- Launch a basic Compute Engine VM instance
- SSH into the instance
- Understand basic configuration options

## 🛠️ Prerequisites

- A Google Cloud project with billing enabled
- Basic familiarity with GCP Console or `gcloud` CLI
- Enabled Compute Engine API

## 🚀 Steps

### Step 1: Enable the Compute Engine API

If not already enabled:

```bash
gcloud services enable compute.googleapis.com
```
Or through the GCP Console:
1. Go to APIs & Services > Library
2. Search for Compute Engine API
3. Click Enable

### Step 2: Create a VM via Console
1.	Go to Compute Engine > VM Instances
2.	Click “Create Instance”
3.	Set:
    - Name: my-first-vm
    - Region: us-central1
    - Zone: us-central1-a
    - Machine type: e2-micro (eligible for free tier)
4.	Under Boot disk, select:
    - OS: Debian
    - Version: Debian 11
5.	Leave firewall options enabled (if needed)
6.	Click Create

### Step 3: Create a VM via CLI

```bash
    gcloud compute instances create my-first-vm \
    --zone=us-central1-a \
    --machine-type=e2-micro \
    --image-family=debian-11 \
    --image-project=debian-cloud \
    --tags=http-server,https-server
```

### Step 4: Connect to the VM

1. Using GCP Console
   - Click SSH next to your VM
2. Using CLI:
    ```bash
    gcloud compute ssh my-first-vm --zone=us-central1-a
    ```

### Step 5: Install a Web Server (Optional)
```bash
    sudo apt update
    sudo apt install apache2 -y
```
View your VM’s external IP in the browser to confirm the Apache welcome page is loading.

### Step 6: Clean Up (Optional)

```bash
    gcloud compute instances delete my-first-vm --zone=us-central1-a
```

## ✅ Summary

You created a virtual machine instance using both the GCP Console and CLI. You connected via SSH and optionally deployed a simple web server.

## 📚 References
 - [Compute Engine Documentation](https://cloud.google.com/compute/docs)
 - [GCP Free Tier](https://cloud.google.com/free)
