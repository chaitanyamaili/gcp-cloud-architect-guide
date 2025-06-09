# Designing and Planning a Cloud Solution Architecture

 - KPIs (Key Performance Indicators)
 - TCO (Total Cost of Ownership)
 - Managed Services
 - System Integration
 - Compliance
 - Security
 - ROI (Return On Interest/Ownership)

## KPIs

KPIs are metrics that matter. They help you track progress toward goals and help you make data-driven decisions

### Uptime checks
  - High uptime means the system is reliable
  - Low uptime means the system is not reliable and may cause more cost
  - Ideal Uptime should be 99 percentile or more for the application/service/system

### Response time

Response time is the duration between when a client sends a request to a cloud service and when it receives the complete response

Ideal response time for the application should be 200ms or lower

#### Components of Response Time

 - Network latency – Time for the request to travel over the network.
 - Service processing time – Time the cloud service takes to handle the request.
 - Backend/database latency – Time spent querying databases or calling downstream services.
 - Network return time – Time to send the response back to the client.

### Cost for workload

Workload cost is the aggregated cost of all cloud resources (compute, storage, network, etc.) used to execute a specific workload (e.g., a web app, batch job, microservice, or data pipeline).

Ideal case Workload should be minimal but should meet the define KPIs of the system.

## TCO (Total Cost of Ownership)

TCO is the total cost of acquiring, operating, and maintaining a cloud service over its full lifecycle — including direct, indirect, and lifecycle costs.

### Direct cost

Costs that are directly billed or clearly attributable to the use of cloud resources

Examples:
- Compute: VM instances, serverless execution
- Storage: Object, block, and file storage
- Networking: Bandwidth charges, inter-region traffic
- Databases: Cloud SQL, BigQuery, Spaner usage
- Licenses: OS, DB, application licenses

### Indirect cost

Hidden or less-visible costs that impact operations and productivity, not directly on the cloud bill

Examples:
- Training: Upskilling teams to work with cloud tools
- Migration: Planning, re-architecting, and downtime during migration
- Security and Compliance: Third-party audits, tools, and staff effort
- Vendor Lock-in Risk: Potential future costs of switching providers
- Productivity Gains/Losses: From automation or tooling changes

### Lifecycle cost

Total cost of the cloud service across all phases: acquisition → usage → decommissioning

Examples:
- Acquisition: Initial setup, service provisioning, migration
- Operations: Ongoing usage charges, scaling, maintenance
- Support: Premium support plans, incident management
- Decommissioning: Data egress, backup archiving, service teardown

## Managed Services

- Less config/operation
- Automate common task
- Expose difficult funtionality: AutoML
- Little competative advantage to doing yourself

## System Integrations

Consist of Storage Integrations, and also cost optimizations.

## Compliance

Cloud compliance refers to the alignment of cloud-based operations and configurations with applicable regulations, standards, and internal controls to ensure lawful, ethical, and secure use of cloud services.

Examples
| Standard | Applies to |
| ---------|------------|
|GDPR| Personal data of EU citizens |
|HIPAA|U.S. healthcare data|
|SOC 2|SaaS and service providers (trust principles)|
|PCI-DSS|Payment card data|
|ISO 27001|Information security management systems|

## Security

Cloud security focuses on protecting cloud-based systems and data against unauthorized access, breaches, misuse, and loss — while ensuring systems remain reliable and trustworthy.

### Confidentiality

Ensures that data is accessible only to authorized users and systems.

Key Practices:
- Authentication & Authorization (e.g., IAM, MFA)
- Data Encryption (at rest and in transit)
- Network isolation (VPCs, firewalls)
- Access control policies (RBAC, IAM policy)
- Secrets management (e.g., Cloud Secrets)

### Integrity

Ensures that data is accurate, consistent, and has not been tampered with.

Key Practices:
- Checksums and hash validation
- Versioning and audit logs
- Digital signatures
- Immutable storage
- Database integrity constraints

### Availability

Ensures that cloud services and data are available when needed, even during failures or attacks.

Key Practices:
- Redundancy and failover (multi-zone, multi-region)
- Auto-scaling and load balancing
- DDoS protection (e.g., Cloud Armor, AWS Shield)
- Backups and disaster recovery plans
- SLAs and uptime monitoring

## ROI (Return On Interest/Ownership)

Return on Investment (ROI) for GCP refers to the quantifiable value and benefits you gain from moving to or building on Google Cloud, relative to the costs incurred

### Measuring value of your investment

Evaluate the value of using GCP by measuring:
- Revenue impact from faster product releases or improved services.
- Time saved on infrastructure setup, scaling, and maintenance.
- Improved reliability and security through managed services.
- Lower risk due to built-in compliance and automated backups.

Common KPIs:
- Time to deploy new apps (before vs after GCP)
- Cost per transaction or API call
- Performance metrics (latency, availability)
- Customer satisfaction (CSAT, NPS)

### Cost Saving (Reduced Capex and Opex)

Capital Expenditure (CapEx) Reduction:
- No need to purchase and manage physical hardware.
- Avoid long-term data center leases.

Operational Expenditure (OpEx) Optimization:
- Pay-as-you-go pricing with per-second billing.
- Auto-scaling resources reduce over-provisioning.
- Sustained use and committed use discounts lower compute cost.
- Managed

### Agility: Increased speed of development

GCP improves agility by enabling faster, more flexible development cycles:
- Infrastructure as Code (Terraform, Deployment Manager) for rapid provisioning.
- Serverless platforms (Cloud Run, Firebase, Functions) to focus on code, not infrastructure.
- CI/CD tools (Cloud Build, Artifact Registry) for streamlined release pipelines.
- AI/ML APIs for plug-and-play innovation (Vision, Translation, Vertex AI).

Benefits:
- Reduce time to market.
- Faster experimentation and iteration.
- Real-time scaling without manual intervention.
