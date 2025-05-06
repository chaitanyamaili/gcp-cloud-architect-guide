# 📚 GCP Exam Case Studies (Analysis & Solution Patterns)

The GCP Professional Cloud Architect exam often includes real-world case studies. Understanding how to approach these scenarios and align solutions with GCP services is critical.

This document outlines:
- Key questions to ask during case analysis
- Sample case study breakdowns
- Common architectural patterns

## 🧠 Case Study Analysis Framework

Use this checklist when reviewing a case study:

### 1. **Business Requirements**
- What are the company’s business goals?
- Is scalability, reliability, or cost a top priority?
- Are there any regional restrictions?

### 2. **Technical Requirements**
- Expected load or performance needs?
- Required services (batch, stream, storage, etc.)?
- Security or compliance constraints?

### 3. **Existing Environment**
- On-prem? Hybrid? Cloud-native?
- Legacy systems or vendor lock-in?
- Current CI/CD, networking, auth setup?

### 4. **Goals & Constraints**
- Migration deadlines?
- Licensing or operational limits?
- Budget constraints?

## 📘 Sample Case Study: Mountkirk Games

**Business Requirements:**
- Launch a new multiplayer game backend
- Global availability and low latency
- Ability to handle spikes during events

**Technical Requirements:**
- Server-side logic in Python
- Store game state and player info
- Analytics pipeline for user behavior

**Solution Outline:**
- Use **Cloud Run** or **GKE Autopilot** for containerized game backend
- Use **Firestore** for game state (NoSQL)
- Use **Pub/Sub + Dataflow + BigQuery** for analytics pipeline
- Use **Cloud Armor** for DDoS protection

## 📘 Sample Case Study: TerramEarth

**Business Requirements:**
- Improve predictive maintenance using IoT sensors
- Machine learning to detect early failure patterns
- Ensure data privacy and compliance

**Technical Requirements:**
- Ingest millions of messages per day
- Integrate with ML pipelines
- Long-term storage of data

**Solution Outline:**
- Use **IoT Core** + **Pub/Sub** for ingestion
- Store raw data in **Cloud Storage**, structured in **BigQuery**
- Train models using **Vertex AI** or **AI Platform**
- Use **VPC Service Controls** for data security

## 📘 Sample Case Study: Dress4Win

**Business Requirements:**
- Migrate from on-prem to GCP with minimal downtime
- Ensure app availability and performance

**Technical Requirements:**
- LAMP stack with heavy relational DB usage
- Frontend APIs need load balancing
- Gradual migration strategy

**Solution Outline:**
- Use **Migrate for Compute Engine** for VM lift-and-shift
- Use **Cloud SQL** for managed MySQL
- Use **Cloud Load Balancing + Cloud CDN**
- Use **Stackdriver Monitoring** for performance

## 🧩 Common Patterns in Case Studies

| Pattern                       | GCP Services |
|------------------------------|--------------|
| Real-time data analytics     | Pub/Sub + Dataflow + BigQuery |
| Web/mobile backend           | Cloud Run / GKE + Firebase/Auth |
| Migration from on-prem       | Transfer Appliance + Migrate for Compute Engine |
| Hybrid networking            | Cloud Interconnect / VPN + Shared VPC |
| ML-based automation          | Vertex AI / AutoML |
| Resilient storage            | Cloud Storage + Object Lifecycle + Multi-region |

## ✅ Tips for Case Study Questions

- Match each requirement to **1 or 2 GCP services**.
- Choose **managed** and **serverless** options when possible.
- Consider **cost, security, and scale** for trade-offs.
- Avoid re-architecting unless explicitly required.
- Understand **migration stages** (lift-and-shift → refactor).

## 📚 Additional Resources

- [Mountkirk Games Example (Qwiklabs)](https://www.qwiklabs.com/)
- [TerramEarth Sample Solution (Coursera)](https://www.coursera.org/)
- [GCP Exam Guide](https://cloud.google.com/certification/cloud-architect)
