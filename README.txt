
# SailPoint IdentityIQ Hospital RBAC Lab Project

This repository contains a complete role-based access control (RBAC) simulation project for a hospital environment implemented in SailPoint IdentityIQ. It includes:

## 📁 Project Structure

- `Hospital_Role_Architecture_DemoData.xlsx`: Base source data for departments, job titles, applications, and entitlements.
- `Hospital_Role_Model_Expanded.xlsx`: IT, Business, and Organization roles with pivoted role matrix.
- `Hospital_Role_Model_Summary.pptx`: Executive summary slides.
- `SailPoint_Role_Model_Gantt.png / .csv`: Implementation timeline and project phases.
- `SailPoint_JML_Simulation.xlsx / .csv`: Joiner–Mover–Leaver lifecycle scenarios.
- `IT_Roles.xml`: SailPoint-importable IT Roles XML.
- `Business_Roles.xml`: SailPoint-importable Business Roles XML.
- `Organization_Roles.xml`: SailPoint-importable Organization Roles XML.
- `SailPoint_AD_App_Role_Mapping.xlsx`: Mapping between business roles and AD/app entitlements.
- `Provisioning_Policies.xml`: Sample provisioning logic per application.
- `Approval_Workflows.xml`: Approval routing for access requests.
- `SailPoint_JML_IdentitySimulation.xml`: Lifecycle simulation of identities.
- `Identity_Refresh_Task.xml`: Task to trigger identity refresh.
- `Entitlement_Aggregation_Task.xml`: Task to aggregate AD and app entitlements.

## 🚀 How to Use

1. Import XMLs via SailPoint Debug > Import From File or Task Scheduler.
2. Configure applications (AD, HIS, SAP, etc.) with matching schemas.
3. Run Identity Refresh and Aggregation tasks.
4. Observe automated provisioning and lifecycle transitions.

## 🛠 Designed For

- IAM professionals
- IdentityIQ training environments
- Demo & PoC setups
- Role modeling exercises

MIT License. Educational Use Only.
