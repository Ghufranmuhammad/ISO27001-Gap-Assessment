# People Controls Summary (ISO 27002:2022 Theme 6)

This document breaks down the core human-centric controls of ISO 27002, detailing how organizations minimize personnel-related security incidents.

---

### 6.1 Screening
*   **Purpose:** To verify that all prospective employees, contractors, and third-party users are trustworthy and capable before onboarding.
*   **Why it matters:** Mitigates the danger of intentional corporate espionage, background fraud, or accidental data handling risks by malicious or unqualified hires.
*   **DesertTech Solutions Implementation:** All final-round candidates undergo criminal background checks, employment history verifications, and professional reference validations handled by an external screening service.
*   **Audit Evidence:** Anonymized, dated screening clearance status reports kept securely in the corporate HR portal.

### 6.2 Terms and Conditions of Employment
*   **Purpose:** To define contractual security requirements and obligations for workers throughout their period of employment.
*   **Why it matters:** Establishes clear, legally enforceable rules about information classification, data privacy, and intellectual property ownership.
*   **DesertTech Solutions Implementation:** Employment offers feature embedded security clauses, data handling agreements, and intellectual property assignments that must be countersigned before Day 1.
*   **Example Audit Evidence:** Employee-signed digital employment contracts matching active system user records.

### 6.3 Information Security Awareness, Education, and Training
*   **Purpose:** To ensure that personnel are fully aware of threat vectors, corporate policies, and their individual security roles.
*   **Why it matters:** The human element remains the most commonly targeted exploit vector. Continual conditioning significantly drops attack success rates.
*   **DesertTech Solutions Implementation:** Automated monthly 10-minute micro-learning modules distributed on a dedicated learning portal coupled with regular phishing assessments.
*   **Example Audit Evidence:** Exported training completion logs showing percentage metrics, alongside historical phishing metrics dashboards.

### 6.4 Disciplinary Process
*   **Purpose:** To execute formalized actions against personnel who break established information security policies.
*   **Why it matters:** Protocols without consequences are ignored. A formal process deters malicious behavior and curbs systematic negligence.
*   **DesertTech Solutions Implementation:** A documented progressive discipline matrix (Verbal Warn -> Written Warn -> Suspension -> Dismissal) clearly written into the corporate handbook.
*   **Example Audit Evidence:** Employee handbook receipt confirmations alongside redacted documentation of historical disciplinary escalations.

### 6.5 Responsibilities After Termination or Change of Employment
*   **Purpose:** To ensure that assets, system access, and intellectual obligations remain secure when someone departs or shifts roles.
*   **Why it matters:** Prevents "zombie access rights" where ex-employees pull sensitive documentation, or corporate items go missing.
*   **DesertTech Solutions Implementation:** Automated offboarding scripts that shut down Active Directory, VPN, and cloud environments within 1 hour of termination, paired with a mandatory physical equipment collection.
*   **Example Audit Evidence:** Signed HR exit checklist documents paired with IAM system lifecycle logs showing exact user deletion timestamps.

### 6.6 Confidentiality or Non-Disclosure Agreements (NDAs)
*   **Purpose:** To legally bind workers and vendors to maintain confidentiality regarding trade secrets and corporate intellectual property.
*   **Why it matters:** Protects corporate competitive advantage and provides legal recourse options in the event of proprietary leaks.
*   **DesertTech Solutions Implementation:** Standardized corporate NDA agreements signed at onboarding, with review points built whenever employees join high-clearance engineering projects.
*   **Example Audit Evidence:** A centralized document management folder holding valid, countersigned NDAs for all active staff and vendors.

### 6.7 Remote Working
*   **Purpose:** To safeguard systems, information, and hardware being processed outside the corporate office perimeter.
*   **Why it matters:** Public Wi-Fi connections, physical device theft, and household shoulder-surfing present massive attack surfaces if not managed.
*   **DesertTech Solutions Implementation:** Mandatory corporate VPN with Always-On routing, Mobile Device Management (MDM) disk encryption, and a strict no-personal-device policy.
*   **Example Audit Evidence:** Central MDM system policy dashboards proving active full-disk encryption and remote wiping capabilities.

### 6.8 Information Security Event Reporting
*   **Purpose:** To enable personnel to rapidly report suspected, potential, or actual security events through clear corporate channels.
*   **Why it matters:** Quick detection and reporting minimize a hacker's lateral movement window during an ongoing breach.
*   **DesertTech Solutions Implementation:** Deployment of a one-click "Report Phishing" utility extension across company email clients, which immediately forwards threats directly into our SOC.
*   **Example Audit Evidence:** Consolidated SOC ticketing reports displaying recorded times from initial user submission to analysis completion.
