# Streamlining-IT-Procurement-Automating-Standard-Laptop-Orders-With-Flow-Designer
ServiceNow ACL &amp; User Administration Project 
# ServiceNow Standard Laptop Request Automation & Security Configuration

## 📌 Project Overview
This project demonstrates end-to-end request fulfillment automation and Access Control List (ACL) security configuration in ServiceNow, completed as part of the Naan Mudhalvan SkillWallet program.

The objective was to automate the standard laptop request process using Flow Designer while enforcing proper user administration, access control, and task routing for IT procurement.

---

## 🛠️ Complete Project Breakdown & Milestones

### 1. User Administration & Access Control Lists (ACLs)
- **User Setup:** Configured system users such as `EEE User` in the `sys_user` table and assigned required roles.
- **Security & ACLs:** Enabled appropriate security privileges such as `security_admin` and implemented CRUD-level ACL rules (`READ`, `CREATE`, `WRITE`, `DELETE`) to restrict table and record access.
- **Objective:** Ensure that only authorized users and roles can create, read, update, or delete relevant records while maintaining secure access control.

### 2. Milestone 1: Flow Implementation
- **Duration:** 40 minutes
- **Objective:** Design and build the `Standard Laptop Task Flow` using Flow Designer.
- **Trigger:** Listens for Requested Items (`sc_req_item`) reaching the configured approval state.
- **Action:** Automatically creates a Catalog Task (`sc_task`) linked to the Requested Item and assigns it to the **Hardware** group for laptop configuration.

### 3. Milestone 2: Flow Assignment
- **Duration:** 11 hours 40 minutes
- **Objective:** Map the `Standard Laptop` catalog item directly to the `Standard Laptop Task Flow`.
- **Execution Logic:** Ensures that whenever an end-user orders a standard laptop, the custom Flow Designer workflow is automatically bound to the request context (`sys_flow_context`).

### 4. Milestone 3: Service Catalog Integration
- **Duration:** 20 minutes
- **Objective:** Publish and configure the `Standard Laptop` catalog item in the Service Catalog portal.
- **Execution Logic:** Enables end-users to submit laptop requests, triggering the approval flow and automated task routing to the **Hardware** team.

### 5. Conclusion & Project Impact
- **Duration:** 10 minutes
- **Summary:** Automating the laptop procurement pipeline eliminates manual ticket routing, accelerates provisioning, and improves IT service delivery while maintaining secure access through ACL enforcement.

---

## ⏱️ Total Project Time Breakdown

| Phase / Milestone | Allocated Duration | Objective |
| :--- | :--- | :--- |
| **User Administration & ACL Setup** | 30 mins | Role and access configuration |
| **Milestone 1** | 40 mins | Flow creation in Flow Designer |
| **Milestone 2** | 11 hrs 40 mins | Linking catalog item to flow |
| **Milestone 3** | 20 mins | Service Catalog item configuration |
| **Conclusion** | 10 mins | Project review and documentation |
| **Total Duration** | **12 hrs 50 mins** | Complete pipeline execution |

---

## 📸 Proof of Work & Verification Screenshots

1. `01_user_and_acl_setup.png` – User creation (`sys_user`) and ACL security configuration.
2. `02_flow_designer.png` – `Standard Laptop Task Flow` trigger and action steps in Flow Designer.
3. `03_flow_assignment.png` – Catalog item mapping to the Flow Designer flow.
4. `04_service_catalog_submission.png` – Submitting the Standard Laptop request and verifying task creation assigned to the Hardware team.

---

## ✅ Project Outcome
This project successfully demonstrates how ServiceNow can be used to automate standard hardware procurement requests while ensuring secure user access and proper task assignment. It highlights the practical use of Flow Designer, ACLs, catalog integration, and IT service automation in a real-world enterprise environment.





