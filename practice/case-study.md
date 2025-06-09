# 📘 GCP Professional Cloud Architect – Case Study Summaries

These case studies are featured in the actual certification exam. You must understand each company’s business and technical requirements, existing architecture, and goals to answer scenario-based questions correctly.

## 🕹️ Mountkirk Games

Industry: Gaming
Goal: Launch new multiplayer game backend with high scalability and low latency.

✅ Key Requirements
 - Global availability, zero downtime
 - Scalable microservices backend
 - Real-time analytics and event logging
 - Low-latency gameplay experience

🛠️ Solution Patterns
 - Cloud Run / GKE Autopilot for backend
 - Pub/Sub + BigQuery + Dataflow for analytics
 - Cloud Spanner or Firestore for game state
 - Cloud Load Balancing + Cloud CDN

## 🚜 TerramEarth

Industry: Manufacturing (Heavy equipment)
Goal: Enable predictive maintenance and ML with IoT data.

✅ Key Requirements
 - Ingest telemetry data from 500k+ vehicles
 - Real-time analytics and ML for failure prediction
 - Compliance with global data policies
 - Batch and streaming pipelines

🛠️ Solution Patterns
 - Cloud IoT Core + Pub/Sub for ingestion
 - BigQuery for warehousing
 - Vertex AI for model training and deployment
 - Cloud Storage for raw/batch data
 - Dataflow for ETL/streaming

## 👗 Dress4Win

Industry: E-commerce/Online Retail
Goal: Migrate legacy applications from on-prem to GCP.

✅ Key Requirements
 - Reduce cost and maintenance
 - Preserve existing CI/CD workflows
 - Ensure secure, low-downtime migration
 - Leverage containers and managed services

🛠️ Solution Patterns
 - Migrate for Compute Engine for lift-and-shift VMs
 - Cloud SQL / Cloud Spanner for database migration
 - Cloud Load Balancing + Cloud CDN for performance
 - Cloud Monitoring + Logging for observability
 - Anthos (if hybrid strategy considered)

## 📱 Helix Media

Industry: Digital Media & Streaming
Goal: Serve personalized content to millions of users with near-real-time recommendations.

✅ Key Requirements
 - Scalable content delivery system
 - Personalized user experiences via ML
 - Cost-effective global content serving
 - Low-latency user analytics and processing

🛠️ Solution Patterns
 - Cloud Storage + Cloud CDN for media delivery
 - BigQuery ML or Vertex AI for recommendations
 - Cloud Run / App Engine for APIs
 - Pub/Sub + Dataflow for event tracking

## 🏦 Cetrus Financial

Industry: Financial Services
Goal: Modernize core banking system with strong security and compliance.

✅ Key Requirements
 - Data encryption and residency compliance
 - Reliable transaction systems
 - Support for disaster recovery and backups
 - Zero-trust and least privilege access

🛠️ Solution Patterns
 - Cloud HSM + Cloud KMS + CMEK
 - VPC Service Controls + Private Google Access
 - Cloud Spanner or Cloud SQL (HA) for core banking DB
 - Security Command Center, IAM Conditions, Cloud Armor

✅ How to Study These

Tip	Strategy
1.	Memorize business & technical goals for each company
2.	Map service choices to tradeoffs (e.g., cost vs latency)
3.	Think like an architect: reliability, automation, scalability
4.	Practice using diagrams and quick sketches of solutions
5.	Look out for GCP-native tools that reduce ops complexity

📚 Official Links
 - GCP Case Studies (Official PDF)
 - Practice Exams

⸻

These case studies are central to the exam—understand them deeply and tie each requirement to specific GCP solutions.
Would you like these summaries turned into flashcards or a visual mind map?