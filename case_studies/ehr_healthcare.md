# EHR Healthcare – Case Study

EHR Healthcare is a leading provider of electronic health record (EHR) software, offering services to multinational medical offices, hospitals, and insurance providers. ￼

## 🏢 Company Overview
 - Business Model: Software as a Service (SaaS) for electronic health records
 - Clients: Multinational medical offices, hospitals, and insurance providers
 - Growth: Experiencing exponential year-over-year growth due to rapid changes in the healthcare and insurance industry ￼

## 💡 Solution Concept

To accommodate rapid growth and evolving industry demands, EHR Healthcare has selected Google Cloud to replace its current colocation facilities. This strategic move aims to: ￼
 - Scale the environment efficiently
 - Adapt disaster recovery plans
 - Implement continuous deployment capabilities for faster software updates ￼

## 🖥️ Existing Technical Environment
 - Hosting: Multiple colocation facilities; one data center lease is nearing expiration
 - Applications: Web-based customer-facing applications, many containerized and running on Kubernetes clusters
 - Databases: Combination of relational and NoSQL databases, including MySQL, MS SQL Server, Redis, and MongoDB
 - Legacy Systems: Several on-premises file- and API-based integrations with insurance providers, scheduled for replacement over the next few years; no immediate plans for upgrades or migration
 - User Management: Microsoft Active Directory
 - Monitoring: Various open-source tools; alerts are sent via email and are often ignored ￼

## 📈 Business Requirements
 - Onboard new insurance providers as quickly as possible
 - Ensure a minimum of 99.9% availability for all customer-facing systems
 - Provide centralized visibility and proactive action on system performance and usage
 - Enhance ability to provide insights into healthcare trends
 - Reduce latency for all customers
 - Maintain regulatory compliance
 - Decrease infrastructure administration costs
 - Generate predictions and reports on industry trends based on provider data ￼

## 🛠️ Technical Requirements
 - Maintain legacy interfaces to insurance providers with connectivity to both on-premises systems and cloud providers
 - Provide a consistent management approach for container-based customer-facing applications
 - Establish secure and high-performance connections between on-premises systems and Google Cloud
 - Implement consistent logging, log retention, monitoring, and alerting capabilities
 - Manage multiple container-based environments effectively
 - Enable dynamic scaling and provisioning of new environments
 - Develop interfaces to ingest and process data from new providers ￼ ￼ ￼

## 🗣️ Executive Statement

“Our on-premises strategy has worked for years but has required a major investment of time and money in training our team on distinctly different systems, managing similar but separate environments, and responding to outages. Many of these outages have been a result of misconfigured systems, inadequate capacity to manage spikes in traffic, and inconsistent monitoring practices. We want to use Google Cloud to leverage a scalable, resilient platform that can span multiple environments seamlessly and provide a consistent and stable user experience that positions us for future growth.”

## Reference
 - [ehr_healthcare](https://services.google.com/fh/files/blogs/master_case_study_ehr_healthcare.pdf)