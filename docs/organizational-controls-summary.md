# Organizational Controls Summary (Controls 5.1 - 5.10)

This document breaks down the first 10 Organizational Controls from ISO 27002, contextualized for our operations at DesertTech Solutions.

---

### 5.1 Policies for Information Security
*   **Purpose:** To define management direction and support for information security across the organization.
*   **Why it matters:** Without a foundational policy, security efforts are ad-hoc, inconsistent, and lack executive backing.
*   **DesertTech Solutions Implementation:** An annual executive-approved "Information Security Master Policy" published on the company intranet for all staff.
*   **Example Audit Evidence:** Document control history showing annual review, executive sign-off, and intranet read-receipt logs.

### 5.2 Information Security Roles and Responsibilities
*   **Purpose:** To define and assign security duties throughout the organization to prevent gaps or overlaps.
*   **Why it matters:** If everyone is responsible for security, nobody is. Clear ownership ensures accountability.
*   **DesertTech Solutions Implementation:** Security responsibilities are explicitly written into HR job descriptions (e.g., IT Admin, DevOps Lead) and the CISO's charter.
*   **Example Audit Evidence:** Signed employment contracts with attached role descriptions; organizational chart showing the security reporting line.

### 5.3 Segregation of Duties
*   **Purpose:** To prevent fraud, errors, and unauthorized activities by splitting conflicting responsibilities among different people.
*   **Why it matters:** One single person should never have the power to initiate, approve, and execute a critical transaction or system change without oversight.
*   **DesertTech Solutions Implementation:** The developer who writes code cannot approve their own pull request or push code directly to the production cloud environment.
*   **Example Audit Evidence:** GitHub pull request logs showing mandatory peer review and segregated production deployment permissions.

### 5.4 Management Responsibilities
*   **Purpose:** To ensure managers actively advocate for, implement, and enforce security policies within their teams.
*   **Why it matters:** Security culture thrives or dies based on leadership behavior. Managers must lead by example and hold teams accountable.
*   **DesertTech Solutions Implementation:** Mandatory quarterly security briefing attendance for all department heads, with security KPIs tied to manager bonuses.
*   **Example Audit Evidence:** Management review meeting minutes and performance review templates showing security compliance metrics.

### 5.5 Contact with Authorities
*   **Purpose:** To maintain established channels with legal, regulatory, and law enforcement bodies in the event of an incident.
*   **Why it matters:** When a breach or regulatory crisis occurs, scrambling for the right contact phone number wastes critical incident response time.
*   **DesertTech Solutions Implementation:** A registry within our Incident Response Plan detailing contact points for local data protection authorities and cybercrime units.
*   **Example Audit Evidence:** The "External Authority Contact List" document, verified and updated within the last 12 months.

### 6.6 Contact with Special Interest Groups
*   **Purpose:** To engage with security forums, professional associations, and threat intelligence groups.
*   **Why it matters:** Security threats evolve rapidly. Staying siloed means missing out on early warnings about new vulnerabilities and industry best practices.
*   **DesertTech Solutions Implementation:** Corporate memberships in ISACA, OWASP, and local threat-sharing forums (ISACs).
*   **Example Audit Evidence:** Valid corporate subscription invoices and active staff login accounts to professional security portals.

### 5.7 Threat Intelligence
*   **Purpose:** To gather, analyze, and act upon information regarding active external information security threats.
*   **Why it matters:** Shift from a reactive "firefighting" security posture to a proactive defense based on real-world hacker tactics.
*   **DesertTech Solutions Implementation:** Automated integration of premium and open-source threat feeds into our SIEM (Security Information and Event Management) system.
*   **Example Audit Evidence:** SIEM configuration screens showing active threat feed API connections and samples of generated threat alerts.

### 5.8 Information Security in Project Management
*   **Purpose:** To integrate security checkpoints into all project lifecycles from the very beginning.
*   **Why it matters:** "Bolting on" security to a finished project is vastly more expensive and less effective than designing it securely by default.
*   **DesertTech Solutions Implementation:** A mandatory Security Risk Assessment phase built directly into our Jira project creation workflow.
*   **Example Audit Evidence:** Completed project charter documents containing signed-off security and privacy impact assessments.

### 5.9 Inventory of Information and Other Associated Assets
*   **Purpose:** To identify and maintain a complete record of all corporate data, software, hardware, and services.
*   **Why it matters:** You cannot protect or monitor what you do not know you own.
*   **DesertTech Solutions Implementation:** A centralized asset management database (CMDB) that auto-scans the corporate network and cloud environments.
*   **Example Audit Evidence:** Exported CSV/spreadsheet of the live asset inventory showing owners, classifications, and hardware locations.

### 5.10 Acceptable Use of Information and Other Associated Assets
*   **Purpose:** To define rules for how employees are allowed to use corporate devices, networks, and data.
*   **Why it matters:** Mitigates insider risk, legal liability, and malware entry points by explicitly banning risky behavior (e.g., illegal downloads).
*   **DesertTech Solutions Implementation:** An "Acceptable Use Policy (AUP)" that all employees must read and sign digitally during onboarding.
*   **Example Audit Evidence:** Employee acknowledgement logs from the HR portal confirming signature of the latest AUP.

