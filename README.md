# Streamlining-IT-Procurement-Automating-Standard-Laptop-Orders-With-Flow-Designer
ServiceNow ACL &amp; User Administration Project 
# ServiceNow Standard Laptop Request Automation & Security Configuration

## 📌 Project Overview
This project demonstrates end-to-end request fulfillment automation and Access Control List (ACL) security configuration in ServiceNow, completed as part of the **Naan Mudhalvan SkillWallet** program. It covers user and role administration, CRUD security rules, Flow Designer automation, and Service Catalog integration.
---

## 🛠️ Complete Project Breakdown & Milestones

### **1. User Administration & Access Control Lists (ACLs)**
* **User Setup:** Configured system users (e.g., `EEE User`) in the `sys_user` table and assigned required roles.
* **Security & ACLs:** Elevated security permissions to `security_admin` and implemented CRUD-level Access Control Rules (`READ`, `CREATE`, `WRITE`, `DELETE`) to restrict table and record-level access.

---

### **2. Milestone 1: Flow Implementation**
* **Duration:** 40 minutes.
* **Objective:** Design and build the `Standard Laptop Task Flow` using **Flow Designer**
  * **Trigger:** Listens for Requested Items (`sc_req_item`) reaching the configured approval state.
  * **Action:** Automatically generates a Catalog Task (`sc_task`) linked to the Requested Item and assigns it to the **Hardware** group for laptop configuration.

---

### **3. Milestone 2: Flow Assignment**
* **Duration:** 11 hours 40 minutes
* **Objective:** Map the `Standard Laptop` catalog item directly to the `Standard Laptop Task Flow'
* **Execution Logic:** Ensures that whenever an end-user orders a Standard Laptop, the custom Flow Designer logic is automatically bound to the request context (`sys_flow_context`).

---

### **4. Milestone 3: Service Catalog Integration**
* **Duration:** 20 minutes
* **Objective:** Publish and configure the `Standard Laptop` catalog item in the **Service Catalog** portal.
* **Execution Logic:** Enables end-users to submit laptop requests, initiating the approval chain and automated task routing to the **Hardware** team
---

### **5. Conclusion & Project Impact**
* **Duration:** 10 minutes
* **Summary:** Automating the laptop procurement pipeline eliminates manual ticket routing, speeds up provisioning times, and enhances IT service delivery while maintaining security through ACL rules.

---

## ⏱️ Total Project Time Breakdown

| Phase / Milestone | Allocated Duration | Objective |
| :--- | :--- | :--- |
| **Milestone 1** | 40 mins) | Flow creation in Flow Designer |
| **Milestone 2** | 11 hrs 40 mins | Linking catalog item to flow) |
| **Milestone 3** | 20 mins | Service Catalog item testing[span_30] |
| **Conclusion** | 10 mins | Project review & documentation |
| **Total Duration** | **12 hrs 50 mins** | Complete pipeline execution |

---

## 📸 Proof of Work & Verification Screenshots


1. `01_user_and_acl_setup.png` – User creation (`sys_user`) and ACL security configurations.
2. `02_flow_designer.png` – `Standard Laptop Task Flow` trigger and action steps in Flow Designer.
3. `03_flow_assignment.png` – Catalog item mapping to the Flow Designer flow.
4. `04_service_catalog_submission.png` – Submitting the Standard Laptop request and verifying task creation assigned to the Hardware team
5.
