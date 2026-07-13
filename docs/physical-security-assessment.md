# Physical Security Assessment: DesertTech Solutions

This document presents a fictionalized security assessment identifying physical infrastructure status, gaps, and remediation metrics.

---

### 1. Building Access
*   **Current State:** Main facility doors are managed via an RFID badge system. Security guards man the lobby during regular corporate working hours (08:00 - 18:00).
*   **Gap:** After-hours (18:00 - 08:00) entry relies completely on automatic lock systems with zero active human monitoring.
*   **Recommendation:** Integrate the badge access tracking system with the primary SOC alerting engine to log unexpected night-time entrance alerts automatically.
*   **Priority:** High

### 2. Visitor Management
*   **Current State:** Visitors record entry using a paper sign-in log on the front counter.
*   **Gap:** Identity validation is not performed, and guest sheets are fully exposed to view by anyone standing at the front desk.
*   **Recommendation:** Deploy a dedicated electronic visitor registration kiosk requiring state ID scanning and dynamic printing of temporary badges.
*   **Priority:** Medium

### 3. CCTV
*   **Current State:** Internal cameras look down primary pathways and main entry doors.
*   **Gap:** Significant visual blind spots exist along the rear warehouse delivery doors and side emergency fire exits.
*   **Recommendation:** Deploy 4 additional exterior low-light cameras to provide total coverage of secondary entryways.
*   **Priority:** High

### 4. Server Room Security
*   **Current State:** The server area uses standard combination mechanical keypad locks.
*   **Gap:** Combination codes are shared broadly among staff, and mechanical keypads do not log individual entry timestamps.
*   **Recommendation:** Upgrade the server room door to biometric thumbprint access combined with dual-factor PIN entry.
*   **Priority:** Critical

### 5. Fire Protection
*   **Current State:** Traditional commercial ceiling water sprinklers installed across the main facility spaces.
*   **Gap:** If water sprinklers activate over live compute arrays, they will permanently destroy operational hardware infrastructure.
*   **Recommendation:** Deploy an isolated gaseous FM-200 or clean-agent chemical fire suppression matrix inside the main server space.
*   **Priority:** Critical

### 6. Clean Desk Policy
*   **Current State:** A clean desk policy is officially documented within the corporate handbook.
*   **Gap:** Desks frequently show active sticky notes containing user passwords, alongside unfiled confidential papers.
*   **Recommendation:** Institute a regular weekly after-hours compliance sweep led by security, issuing internal citations for non-compliance.
*   **Priority:** Low

### 7. Equipment Disposal
*   **Current State:** Legacy computing assets are stacked in an open storage room awaiting eventual recycling pickup.
*   **Gap:** Storage disks remain fully intact, creating an opportunistic risk of internal theft and subsequent data exposure.
*   **Recommendation:** Place a heavy secure media bin inside the IT storage zone and ensure drives are wiped immediately upon decommissioning.
*   **Priority:** High

### 8. Environmental Monitoring
*   **Current State:** Simple ambient wall thermostats display temperature inside the server environment.
*   **Gap:** No automated alerts are triggered if internal humidity spikes or an HVAC cooling pump fails overnight.
*   **Recommendation:** Install an interconnected IoT humidity and liquid sensor grid that messages the on-call SOC engineer the moment tolerances shift.
*   **Priority:** Medium
