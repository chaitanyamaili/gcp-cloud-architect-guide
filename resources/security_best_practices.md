# GCP Security Best Practices

Security in Google Cloud Platform (GCP) is a shared responsibility between Google and the user. This document provides a comprehensive overview of best practices to secure your GCP resources, data, and users.

---

## 🔐 Identity & Access Management (IAM)

- **Principle of Least Privilege**: Grant only the minimum permissions needed to users, service accounts, and groups.
- **Use Predefined Roles Over Basic Roles**: Avoid `Owner`, `Editor`, `Viewer`. Prefer fine-grained predefined or custom roles.
- **Service Accounts**:
  - Use separate service accounts for each application or service.
  - Avoid reusing default service accounts.
  - Rotate service account keys regularly.
- **Use IAM Conditions** for context-aware access (e.g., IP, device security level).
- **Enable Organization Policy Constraints** to enforce rules across your projects.

---

## 🔐 Authentication & Authorization

- **Enable 2-Step Verification (2SV)** for all user accounts.
- **Use Identity-Aware Proxy (IAP)** to secure web apps without needing a VPN.
- **Use Google Cloud Identity** for managing user identities and SSO.

---

## 🗝️ Key & Secret Management

- **Use Secret Manager** for storing API keys, passwords, and tokens.
- **Use Cloud KMS** for encryption key management (integrates with many GCP services).
- **Rotate keys/secrets regularly** and enforce access controls.

---

## 🧱 Network Security

- **Use VPC Firewalls** to control traffic to and from your VM instances.
- **Use Private Google Access** to access GCP APIs without public IPs.
- **Set up VPC Service Controls** for data exfiltration protection.
- **Use Cloud NAT** instead of public IPs for outbound access from private instances.
- **Enable SSL/TLS** for all external and internal communication.

---

## 🔎 Monitoring & Logging

- **Enable Cloud Audit Logs** for all services.
- **Use Cloud Logging and Monitoring** to detect anomalies and alerts.
- **Enable Policy Intelligence tools** to review and optimize IAM policies.
- **Use Security Command Center** (Premium for full features) to detect misconfigurations, vulnerabilities, and threats.

---

## 📦 Data Protection

- **Enable default encryption** (enabled by default in GCP).
- **Use customer-managed encryption keys (CMEK)** or customer-supplied keys (CSK) for sensitive workloads.
- **Classify your data** and apply appropriate protections.

---

## 🚧 Infrastructure Hardening

- **Restrict public IP addresses**; use internal IPs and bastion hosts.
- **Use OS Login and IAM for SSH access** to VMs.
- **Use Shielded VMs** for improved kernel and boot security.
- **Regularly apply OS and software updates**.

---

## 📅 Governance, Compliance & Cost Controls

- **Use Folders and Organizations** to structure resources for policy enforcement.
- **Set up budgets and alerts** to prevent unexpected costs.
- **Enable Org Policy Constraints** to restrict unsafe services or actions.
- **Enable Resource Hierarchy** logging and use tags/labels for auditability.

---

## 🔄 Automation & DevSecOps

- **Automate IAM reviews** and least privilege enforcement using tools like Forseti or Policy Analyzer.
- **Integrate security checks into CI/CD pipelines** with Cloud Build, SAST, and DAST tools.
- **Use Infrastructure as Code (IaC)** and scan for misconfigurations with tools like Terraform + tfsec.

---

## 🧪 Security Testing & Red Teaming

- **Perform regular penetration testing** (following [Google’s policy](https://cloud.google.com/security/penetration-testing)).
- **Use Google Cloud’s Mandiant services** for incident response and threat detection (if applicable).

---

## ✅ Summary Checklist

| Category          | Key Action Items |
|------------------|------------------|
| IAM              | Least privilege, custom roles, audit logs |
| Networking       | Firewall rules, private access, no public IPs |
| Data Protection  | Encryption, key rotation, data classification |
| Monitoring       | Audit logs, SCC, alerting |
| Secrets          | Secret Manager, no hardcoded credentials |
| Access           | OS Login, MFA, Cloud Identity |
| Automation       | IaC, CI/CD security scans, policies |

---

## 📚 Useful Links

- [Google Cloud Security Documentation](https://cloud.google.com/security)
- [IAM Best Practices](https://cloud.google.com/iam/docs/best-practices)
- [Cloud KMS](https://cloud.google.com/kms/docs)
- [Security Command Center](https://cloud.google.com/security-command-center)
- [Cloud Armor & DDoS Protection](https://cloud.google.com/armor)
