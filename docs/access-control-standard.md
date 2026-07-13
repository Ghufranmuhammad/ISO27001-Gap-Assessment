# Access Control Standard
**Document ID:** DTS-STND-04  
**Classification:** Internal Use Only

## 1. Purpose & Scope
This standard defines structural validation baselines for creating, managing, and terminating access privileges across all DesertTech Solutions information networks, operating software environments, and end-user devices.

## 2. User Account Management & Password Requirements
* All access requests must pass an identity check and match documented business needs before clearance.
* Passwords must be a minimum of 14 characters in length, containing uppercase letters, lowercase letters, numbers, and symbols.
* Passwords must not contain personal details or common corporate dictionary terms.
* Passwords must expire and require updating every 90 days if not paired with strong contextual MFA rules.

## 3. Multi-Factor Authentication (MFA)
* Phishing-resistant MFA validation is required for all access to corporate systems, external cloud instances, and administrative accounts.
* MFA is strictly mandatory for any remote connection attempts via VPN or conditional access portals.

## 4. Privileged Access Management (PAM)
* Administrative privileges must be strictly separated from normal daily operational user accounts.
* Administrators must use dedicated admin-only profiles to perform system modifications.
* Just-In-Time (JIT) access tools must be used to grant elevated administrative tokens on a temporary basis, expiring automatically after a maximum of 4 hours.

## 5. User Access Reviews & Account Deprovisioning
* Managers must conduct formal reviews of user access levels every 90 days to eliminate privilege creep.
* Administrative privileges must undergo independent security team reviews every 30 days.
* Upon notification of employee termination, the IT Support team must deprovision and lock all associated user accounts within **2 hours** of the employee's formal departure time.

