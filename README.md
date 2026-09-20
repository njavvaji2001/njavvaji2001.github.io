# 🛡️ Nithin Javvaji | Cybersecurity & GRC Analyst Portfolio

Welcome to my security engineering and risk governance hub. I am a detail-oriented analyst specializing in tracking network threats, investigating system vulnerabilities, and solving complex security problems. I combine a strong foundation in technology management and data-driven analysis to help organizations enforce compliance regulations, manage operational risk, and protect critical data infrastructure.

🎓 **Education:** Master of Science in Technology Management — Avila University
💼 **Professional Experience:** Former Senior Associate at Synchrony Financial
🔗 **Professional Profiles:** [Connect on LinkedIn](https://linkedin.com) | [Main GitHub Repository Hub](https://github.com)

---

## 🚀 Featured Cybersecurity Engineering Projects
### 🏢 Case Study: Enterprise Risk Assessment & Compliance Audit (Botium Toys)
* **Core Skills:** GRC Framework Mapping, NIST CSF, PCI-DSS, GDPR, SOC 2 Compliance, Access Control Auditing.
* **Description:** Executed a comprehensive internal security audit and controls assessment for a mock e-commerce retailer. Evaluated current organizational defenses against established compliance frameworks, identified critical security gaps (lack of encryption, least privilege violations, and unmonitored legacy infrastructure), and generated structured strategic recommendations to mitigate business risk and satisfy international privacy laws.

#### 📊 Controls Assessment Matrix

| Status | Control Audited | Identified Operational Vulnerability |
| :---: | :--- | :--- |
| ❌ | **Least Privilege & IAM** | Access controls are not restricted; employees hold unnecessary privileges to sensitive customer data. |
| ❌ | **Data Encryption** | Account numbers, transaction data, and PII/SPII are processed and stored locally in cleartext. |
| ❌ | **Network Visibility (IDS)** | No Intrusion Detection System is deployed to monitor anomalous network telemetry traffic. |
| ❌ | **Disaster Recovery & Backups** | Complete absence of critical data backups and business continuity frameworks. |
| ❌ | **Legacy Systems Monitor** | Internal legacy systems lack formalized manual monitoring, maintenance, and intervention controls. |
|  | **Firewall & Antivirus** | Perimeter firewall rules and client antivirus agents are successfully deployed and monitored. |

#### ⚖️ Regulatory Compliance Gap Analysis
* **PCI-DSS:** Non-compliant due to unencrypted cardholder data storage and lack of secure password management pipelines.
* **GDPR:** Violates data confidentiality standards because sensitive EU customer PII is accessible to unauthorized internal users.
* **SOC 2 Type II:** Fails core privacy and confidentiality trust principles due to a lack of defined user access policies.

#### 🛠️ Core Remediation Recommendations Submitted to IT Leadership:
1. **Enforce Role-Based Access Controls (RBAC):** Restrict system data access using the Principle of Least Privilege (PoLP) to isolate cardholder environments.
2. **Deploy Cryptographic Controls:** Implement AES-256 encryption configurations for all sensitive customer assets at rest and in transit.
3. **Establish Sentinel Infrastructure:** Integrate a centralized IDS loop and formalize standard manual intervention protocols for legacy environments.

### 📱 OmniScan: Multi-Threaded Network Reconnaissance Utility
* **Core Skills:** Python Automation, Socket Probing, Low-Level Packet Tracking, Network Monitoring, Incident Detection.
* **Description:** Designed and engineered an asynchronous local network discovery application that utilizes concurrent ICMP sweeps to inventory an entire local subnet range in under 5 seconds. Bypasses standard OS privacy limits by securely extracting hardware MAC addresses from native system ARP caches, executing targeted vulnerability port audits (FTP, SSH, HTTP, SMB), and exporting live security telemetry data into downloadable spreadsheet formats.
* [📦 View Source Code & Interactive Documentation](https://github.com/omniscan-network-recon)

---

## 🗂️ Core Competencies & Technical Skills

### 1. Governance, Risk, and Compliance (GRC)
* **Framework Mastery:** Deep conceptual understanding of the **NIST Cybersecurity Framework (CSF)**, **Risk Management Framework (RMF)**, and Security Auditing workflows.
* **Risk & Access Controls:** Well-versed in **Identity & Access Management (IAM)**, Third-Party Risk Management (TPRM), Asset Management systems, and Data Loss Prevention (DLP) protocols to strictly enforce the Principle of Least Privilege.

### 2. Defensive Operations & Application Security
* **Vulnerability Frameworks:** Core focus on tracking **OWASP Top 10** web application risks, specializing in remediating *Broken Access Control* and *Injection Attacks (SQLi)* through proper input sanitization and parameterized query architecture.
* **Network Security Foundations:** Extensively trained in network monitoring tools, secure network models, and role-based access controls (RBAC).

### 3. Technical Security Toolkit
* **SIEM Operations:** Ingestion, query parsing, and log analysis utilizing **Splunk** and **Google SecOps (Chronicle)** platforms.
* **Languages & Automation:** **Python** (Defensive automation scripts), **SQL** (Log querying & data filtering), and **Linux Command Line** system navigation.

---

## 💼 Highlighted Professional Experience

**Synchrony Financial** | Hyderabad, India  
*Senior Associate (2022 – 2024)*
*   Utilized strong analytical thinking and data-driven decision-making skills to evaluate operational trends and implement process improvements, earning an official **Excellence Award**.
*   Collaborated directly with cross-functional leadership to deliver actionable insights based on core business needs, driving team efficiency and customer service enhancements.

---

## 📜 Professional Licenses & Certifications
* **Google Cybersecurity Professional Certificate** | Coursera / Google (In-Progress)
* **Cisco Network Security Certification** | Cisco (Network Models & RBAC)

___

*Thank you for visiting my professional security hub. Feel free to connect with me on LinkedIn to discuss career opportunities, framework compliance, or collaborative security engineering!*
