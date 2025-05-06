# GCP Services Overview

This document summarizes the key Google Cloud Platform (GCP) services organized by domain. It is designed as a quick reference guide for exam preparation and real-world architecture planning.

## ☁️ Compute

| Service                 | Description |
|-------------------------|-------------|
| **Compute Engine**      | Infrastructure-as-a-Service (IaaS) for running virtual machines. |
| **App Engine**          | Platform-as-a-Service (PaaS) for deploying scalable applications. |
| **Cloud Run**           | Fully managed serverless containers (based on Knative). |
| **Cloud Functions**     | Event-driven serverless compute platform for lightweight functions. |
| **GKE (Kubernetes Engine)** | Managed Kubernetes service for container orchestration. |

## 🗃️ Storage & Databases

| Service                 | Description |
|-------------------------|-------------|
| **Cloud Storage**       | Object storage for unstructured data. |
| **Persistent Disks**    | Block storage for VM instances. |
| **Filestore**           | High-performance file storage (NFS). |
| **Cloud SQL**           | Managed SQL databases (MySQL, PostgreSQL, SQL Server). |
| **Cloud Spanner**       | Globally distributed, strongly consistent relational database. |
| **Firestore / Datastore** | NoSQL document database. |
| **Bigtable**            | High-throughput NoSQL wide-column database. |
| **BigQuery**            | Serverless, highly scalable data warehouse. |

## 🌐 Networking

| Service                 | Description |
|-------------------------|-------------|
| **VPC (Virtual Private Cloud)** | Global private network with subnets, routing, and firewalls. |
| **Cloud Load Balancing**| Global and regional load balancing for HTTP(S), TCP, UDP. |
| **Cloud CDN**           | Content delivery network for latency reduction. |
| **Cloud NAT**           | Network Address Translation for private resources. |
| **Cloud Interconnect / VPN** | Hybrid connectivity for on-premises and cloud. |
| **Private Service Connect** | Secure private access to GCP and third-party services. |

## 🔐 Identity & Security

| Service                 | Description |
|-------------------------|-------------|
| **IAM (Identity and Access Management)** | Access control for resources. |
| **Cloud Identity**      | Identity as a Service (IDaaS) for users and groups. |
| **Secret Manager**      | Secure storage for API keys, passwords, and other secrets. |
| **Cloud KMS**           | Key management and encryption. |
| **Access Context Manager** | Define access policies based on attributes. |
| **Security Command Center** | Centralized security and risk management. |

## 📈 Monitoring & Operations

| Service                 | Description |
|-------------------------|-------------|
| **Cloud Monitoring**    | Observability and metrics collection. |
| **Cloud Logging**       | Centralized log collection and analysis. |
| **Cloud Trace**         | Latency analysis tool for apps. |
| **Cloud Profiler**      | Performance profiling tool. |
| **Cloud Debugger**      | Debug production code in real time. |

## 📊 Data Analytics & AI/ML

| Service                 | Description |
|-------------------------|-------------|
| **BigQuery**            | Serverless analytics platform. |
| **Dataflow**            | Managed data processing (Apache Beam). |
| **Dataproc**            | Managed Spark/Hadoop clusters. |
| **Pub/Sub**             | Messaging service for event ingestion. |
| **Vertex AI**           | Unified AI/ML platform for training, deploying, and managing models. |
| **Looker Studio**       | Business intelligence and data visualization. |

## 🧪 Developer Tools & DevOps

| Service                 | Description |
|-------------------------|-------------|
| **Cloud Build**         | CI/CD platform for building and deploying code. |
| **Artifact Registry**   | Store and manage container images and packages. |
| **Source Repositories** | Git repositories hosted by GCP. |
| **Cloud Scheduler**     | Cron jobs and scheduled tasks. |
| **Cloud Tasks**         | Distributed task queue management. |

## 📦 Other Core Services

| Service                 | Description |
|-------------------------|-------------|
| **Cloud Marketplace**   | Preconfigured solutions and partner tools. |
| **Billing and Budgets** | Manage GCP costs and alerting. |
| **Cloud APIs & Endpoints** | Expose and manage APIs with monitoring and authentication. |
| **Cloud Shell**         | In-browser command line with GCP CLI tools. |

## 📚 Useful Links

- [GCP Product List](https://cloud.google.com/products)
- [GCP Documentation](https://cloud.google.com/docs)
- [Certification Guide](https://cloud.google.com/certification/cloud-architect)
