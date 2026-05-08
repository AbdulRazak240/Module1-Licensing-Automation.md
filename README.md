# Project: Automated License Governance & Group Management
## Module 1 | Topic 3: Group-Based Licensing (GBL)

### 🚀 Implementation Overview
I implemented an automated identity governance solution to manage Microsoft 365 license distribution and department-level access control. By moving away from manual assignments, I reduced administrative overhead and ensured zero-error onboarding.

### 🛠️ Key Tasks Performed
- **Group-Based Licensing (GBL):** Assigned M365 licenses to a dynamic group (`DG-All-Members`). Validated that users "inherit" licenses based on their profile metadata.
- **Dynamic Membership Engineering:** Configured and troubleshot complex rule syntax including `-eq`, `-contains`, and `-endsWith`.
- **Role-Based Access Control (RBAC):** Established **Assigned Security Groups** for privileged roles (Global Admins, Identity Admins) to maintain the Principle of Least Privilege.
- **Infrastructure Cleanup:** Validated that **Usage Location (AE)** is a mandatory prerequisite for successful license inheritance.

### 🔍 Technical Validation
- **Inheritance Check:** Verified user profiles showing "Assignment State: Inherited."
- **Syntax Troubleshooting:** Fixed rule failure where `-eq "HR"` was used instead of the exact string `"HR Department"`.
- **Nesting Logic:** Confirmed that Security Groups can be nested to simplify permission inheritance across the tenant.

---
**Status:** Topic 3 Locked 🏆 | **Project:** SC-300 Certification Lab
<img width="1600" height="739" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/ffe901fb-538d-4b13-ba7d-fad640c8bbd4" />

<img width="1600" height="591" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/ea05a5df-51cb-4ca0-a49f-0c69d6e59e9b" />

<img width="1340" height="732" alt="Screenshot (25)" src="https://github.com/user-attachments/assets/c4faee86-ce88-4b4b-9a77-971c8a3f9fba" />




