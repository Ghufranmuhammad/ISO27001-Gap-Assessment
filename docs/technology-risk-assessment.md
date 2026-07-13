# Technology Risk Assessment
**Company:** DesertTech Solutions  
**Framework Alignment:** ISO/IEC 27001 / ISO 27002:2022

This assessment highlights current systemic vulnerability gaps within our operational technology infrastructure and recommends prioritized mitigation tracks.

---

### 1. User Accounts
* **Current State:** Identity profiles are managed through a centralized Identity Provider (IdP). However, stagnant corporate accounts from departed staff are occasionally found active weeks after resignation.
* **Gap:** Lack of automated HR provisioning system links to instantly terminate accounts upon termination.
* **Recommendation:** Implement automated lifecycle hooks between the HR system database and the IdP platform to trigger near-instant account deprovisioning.
* **Priority:** High

### 2. Multi-Factor Authentication (MFA)
* **Current State:** MFA is enabled across standard remote interfaces and primary electronic mail access panels.
* **Gap:** Internal administrative server consoles and secondary local databases allow standard password authentication without secondary prompts.
* **Recommendation:** Mandate phishing-resistant hardware keys or push-notifications with geofencing parameters across all internal administrative workloads.
* **Priority:** Critical

### 3. Endpoint Protection
* **Current State:** Workstations have traditional legacy signature-based antivirus scanners installed.
* **Gap:** Standard antivirus fails to identify modern polymorphic fileless threats and advanced persistent memory injections.
* **Recommendation:** Replace legacy antivirus with an Endpoint Detection and Response (EDR) platform offering automatic machine-learning threat isolation.
* **Priority:** High

### 4. Email Security
* **Current State:** Simple spam rules filter basic keyword-based junk emails.
* **Gap:** Business Email Compromise (BEC) attempts, spear-phishing campaigns, and executive impersonations slip past default keyword filters.
* **Recommendation:** Deploy an Advanced Email Threat Protection (ATP) solution with dynamic link rewriting and sandbox attachment analysis.
* **Priority:** Medium

### 5. Patch Management
* **Current State:** Software updates on operational systems are handled manually by IT support personnel.
* **Gap:** Lack of central reporting dashboards, creating unmonitored tracking lag on missing critical OS updates across remote laptops.
* **Recommendation:** Centralize configuration through a patch management module to automate application updates within 14 days of release.
* **Priority:** Critical

### 6. Backup Strategy
* **Current State:** Weekly full backups are written to network-attached local storage arrays.
* **Gap:** If network-attached backup arrays reside inside the primary active directory domain, modern ransomware will lateral over and encrypt the backups along with live infrastructure.
* **Recommendation:** Deploy a 3-2-1 backup architectural framework featuring off-site, immutable cloud storage locks that cannot be edited or deleted by administrative accounts.
* **Priority:** Critical

### 7. Logging & Monitoring
* **Current State:** Event logs are kept locally on separate server nodes for 30 days before being written over.
* **Gap:** Security analysts lack a single interface to track events across different machines, making cross-platform incident tracking nearly impossible.
* **Recommendation:** Ingest all active directory, endpoint, and firewall logs into a centralized SIEM solution with 90 days of live searchable retention.
* **Priority:** High

### 8. Vulnerability Scanning
* **Current State:** Network perimeter vulnerability checks are performed manually on an annual basis by engineering staff.
* **Gap:** New software flaws are announced daily; annual scans miss newly emerging bugs, leaving a long window of vulnerability exposure.
* **Recommendation:** Deploy automated weekly authenticated internal scans combined with monthly external boundary threat assessments.
* **Priority:** Medium

