# ISO 27002 Technological Controls Summary
**Company:** DesertTech Solutions  
**Framework:** ISO/IEC 27002:2022

This document outlines the core technological controls implemented at DesertTech Solutions to preserve the confidentiality, integrity, and availability of our information assets.

---

### 1. Identity & Access Management (IAM)
* **Purpose:** Ensure only authorized users can access specific organizational systems and data.
* **Risk Addressed:** Unauthorized data access, privilege creeping, and insider threats.
* **Example Implementation at DesertTech Solutions:** Centralized identity provider (IdP) integration managing all employee user accounts with automated role-based access control (RBAC).
* **Example Audit Evidence:** IAM user directory exports, access provision request logs, and current RBAC role mappings.

### 2. Privileged Access Management
* **Purpose:** Restrict and monitor elevated permissions to protect critical infrastructure.
* **Risk Addressed:** Administrative account takeover, unauthorized system modifications, and lateral movement by attackers.
* **Example Implementation at DesertTech Solutions:** Implementation of a Just-In-Time (JIT) privileged access tool requiring dual-authorization for all domain admin and root-level activities.
* **Example Audit Evidence:** Privileged session logs, approved JIT elevation requests, and a list of authorized privileged accounts.

### 3. Authentication
* **Purpose:** Verifiably confirm the identity of a user attempting to access systems.
* **Risk Addressed:** Credential stuffing attacks, brute-force attacks, and compromised passwords.
* **Example Implementation at DesertTech Solutions:** Enforced phishing-resistant Multi-Factor Authentication (MFA) across all corporate applications and VPN gateways.
* **Example Audit Evidence:** MFA configuration status reports, authentication server logs, and system sign-in logs showing MFA challenges.

### 4. Malware Protection
* **Purpose:** Detect, prevent, and remediate malicious software installations on corporate endpoints and servers.
* **Risk Addressed:** Ransomware outbreaks, spyware data exfiltration, and system disruption.
* **Example Implementation at DesertTech Solutions:** Deployment of Endpoint Detection and Response (EDR) agents across all workstations, configured to isolate anomalies automatically.
* **Example Audit Evidence:** EDR central dashboard compliance reports, real-time alert history, and agent version listings.

### 5. Backup Management
* **Purpose:** Maintain redundant copies of critical operational data to ensure resilience against data loss events.
* **Risk Addressed:** Permanent data destruction due to hardware failure, accidental deletion, or ransomware encryption.
* **Example Implementation at DesertTech Solutions:** Automated daily incremental and weekly full backups utilizing the 3-2-1 strategy (3 copies, 2 media types, 1 off-site immutable cloud storage location).
* **Example Audit Evidence:** Backup job completion logs, quarterly disaster recovery restoration test certificates, and cloud storage immutability policies.

### 6. Logging & Monitoring
* **Purpose:** Capture and analyze event generation across the environment to identify suspicious behavior.
* **Risk Addressed:** Undetected security incidents, delayed incident response times, and lack of forensic audit trails.
* **Example Implementation at DesertTech Solutions:** Centralized ingestion of firewall, server, and application logs into a Security Information and Event Management (SIEM) platform analyzed continuously by our security analysts.
* **Example Audit Evidence:** SIEM parsing rules, sample log entries, alert generation histories, and SIEM storage capacity status.

### 7. Vulnerability Management
* **Purpose:** Continually evaluate systems for internal and external security weaknesses.
* **Risk Addressed:** Exploitation of unpatched software flaws, zero-day vulnerabilities, and perimeter breaches.
* **Example Implementation at DesertTech Solutions:** Automated weekly authenticated vulnerability scans across all subnet ranges combined with quarterly external penetration testing.
* **Example Audit Evidence:** Internal vulnerability scanner configuration reports, historical scan remediation tracking sheets, and executive summaries of external penetration tests.

### 8. Encryption
* **Purpose:** Convert sensitive information into ciphertext to protect it at rest and in transit.
* **Risk Addressed:** Interception of network traffic, physical theft of storage media, and unauthorized data viewing.
* **Example Implementation at DesertTech Solutions:** Mandatory AES-256 bit full-disk encryption on all corporate laptops and enforced TLS 1.3 protocol requirements for all external web applications.
* **Example Audit Evidence:** Mobile Device Management (MDM) encryption compliance status reports and web server SSL/TLS configuration checks.

### 9. Secure Configuration
* **Purpose:** Minimize the attack surface by ensuring systems are not deployed with default settings or weak configurations.
* **Risk Addressed:** Exploitation of default passwords, unneccesary open ports, and weak default cryptographic suites.
* **Example Implementation at DesertTech Solutions:** Enforcing baseline operating system hardening templates aligned directly with Center for Internet Security (CIS) Benchmarks via automated group policies.
* **Example Audit Evidence:** Group Policy Object (GPO) configuration exports, gold image deployment templates, and configuration drift alert logs.

### 10. Patch Management
* **Purpose:** Ensure all systems, firmware, and software applications are systematically updated against known flaws.
* **Risk Addressed:** Mass exploitation of publicly documented CVEs (Common Vulnerabilities and Exposures).
* **Example Implementation at DesertTech Solutions:** Automated patching architecture deploying operating system updates within 14 days of release for standard devices and within 72 hours for critical security patches.
* **Example Audit Evidence:** Central patch management dashboard reports showing deployment percentages, missing update lists, and patch validation test logs.

