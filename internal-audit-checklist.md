# ISO 27001:2022 Internal Audit Checklist

## 1. Audit Scope & Objectives
*   **Scope:** All operational processes, infrastructure configurations, and compliance assets managed by DesertTech Solutions LLC, with focus on Cloud Infrastructure, HR Onboarding/Offboarding, and GRC operations.
*   **Objectives:** Verify conformity with ISO/IEC 27001:2022 Clause 8 & Clause 9 requirements; confirm that controls operate as documented; identify non-conformities ahead of external auditing.

---

## 2. Sample Audit Questions & Evidence Requirements

| # | ISO 27001 Clause / Control | Audit Question | Objective Evidence Required |
| :-: | :--- | :--- | :--- |
| 1 | **Clause 8.1** Operational Control | How are planned changes to production infrastructure authorized and verified? | Change management logs, peer review sign-offs in CI/CD pipeline. |
| 2 | **Clause 8.2** Risk Assessment | Is there evidence that a risk assessment was conducted prior to major infrastructure shifts? | Signed risk assessment forms linked to recent cloud architecture adjustments. |
| 3 | **Clause 8.3** Risk Treatment | Where is the risk treatment plan, and how do you track overdue target completion dates? | `risk-treatment-plan.xlsx` showing owner accountability and milestones. |
| 4 | **Annex A 5.15** Access Control | What process ensures that a terminated employee's system access is removed immediately? | Active Directory / IDP de-provisioning logs compared against HR termination dates. |
| 5 | **Annex A 5.17** Auth Info | Is Multi-Factor Authentication (MFA) strictly enforced for all administrative accounts? | Admin console settings export verifying MFA status is set to "Enforced". |
| 6 | **Annex A 7.10** Media Protection | How do we verify that storage media on remote employee laptops is encrypted? | Centralized MDM dashboard report detailing Full Disk Encryption (BitLocker/FileVault) status. |
| 7 | **Annex A 8.14** Redundancy | When was the last time server backups were verified for restoration capability? | Backup validation logs and documented disaster recovery tabletop/restore drill results. |
| 8 | **Clause 9.1** Monitoring | What metrics are used to measure control effectiveness, and who analyzes them? | `grc-kpi-dashboard.xlsx` with monthly/quarterly trends and analysis notes. |
| 9 | **Clause 9.2** Internal Audit | Is there an established audit program that ensures internal reviews are objective and regular? | Approved internal audit schedule, previous internal audit reports, and tracking of findings. |
| 10 | **Clause 9.3** Management Review | How is top management kept informed about the status of security performance metrics? | Management Review Meeting minutes signed by the CEO, including resource allocation notes. |

