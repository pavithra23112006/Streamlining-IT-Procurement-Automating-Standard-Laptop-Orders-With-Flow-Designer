# Streamlining-IT-Procurement-Automating-Standard-Laptop-Orders-With-Flow-Designer
ServiceNow ACL &amp; User Administration Project 
# ServiceNow Standard Laptop Request Automation & Security Configuration

## 📌 Project Overview
This project demonstrates end-to-end request fulfillment automation and Access Control List (ACL) security configuration in ServiceNow, completed as part of the **Naan Mudhalvan SkillWallet** program[span_0](start_span)[span_0](end_span)[span_1](start_span)[span_1](end_span). It covers user and role administration, CRUD security rules, Flow Designer automation, and Service Catalog integration[span_2](start_span)[span_2](end_span)[span_3](start_span)[span_3](end_span)[span_4](start_span)[span_4](end_span)[span_5](start_span)[span_5](end_span).

---

## 🛠️ Complete Project Breakdown & Milestones

### **1. User Administration & Access Control Lists (ACLs)**
* **User Setup:** Configured system users (e.g., `EEE User`) in the `sys_user` table and assigned required roles[span_6](start_span)[span_6](end_span)[span_7](start_span)[span_7](end_span).
* **Security & ACLs:** Elevated security permissions to `security_admin` and implemented CRUD-level Access Control Rules (`READ`, `CREATE`, `WRITE`, `DELETE`) to restrict table and record-level access[span_8](start_span)[span_8](end_span).

---

### **2. Milestone 1: Flow Implementation**
* **Duration:** 40 minutes[span_9](start_span)[span_9](end_span)
* **Objective:** Design and build the `Standard Laptop Task Flow` using **Flow Designer**[span_10](start_span)[span_10](end_span).
* **Execution Logic:**
  * **Trigger:** Listens for Requested Items (`sc_req_item`) reaching the configured approval state[span_11](start_span)[span_11](end_span).
  * **Action:** Automatically generates a Catalog Task (`sc_task`) linked to the Requested Item and assigns it to the **Hardware** group for laptop configuration[span_12](start_span)[span_12](end_span).

---

### **3. Milestone 2: Flow Assignment**
* **Duration:** 11 hours 40 minutes[span_13](start_span)[span_13](end_span)
* **Objective:** Map the `Standard Laptop` catalog item directly to the `Standard Laptop Task Flow`[span_14](start_span)[span_14](end_span).
* **Execution Logic:** Ensures that whenever an end-user orders a Standard Laptop, the custom Flow Designer logic is automatically bound to the request context (`sys_flow_context`)[span_15](start_span)[span_15](end_span)[span_16](start_span)[span_16](end_span).

---

### **4. Milestone 3: Service Catalog Integration**
* **Duration:** 20 minutes[span_17](start_span)[span_17](end_span)
* **Objective:** Publish and configure the `Standard Laptop` catalog item in the **Service Catalog** portal[span_18](start_span)[span_18](end_span).
* **Execution Logic:** Enables end-users to submit laptop requests, initiating the approval chain and automated task routing to the **Hardware** team[span_19](start_span)[span_19](end_span)[span_20](start_span)[span_20](end_span).

---

### **5. Conclusion & Project Impact**
* **Duration:** 10 minutes[span_21](start_span)[span_21](end_span)
* **Summary:** Automating the laptop procurement pipeline eliminates manual ticket routing, speeds up provisioning times, and enhances IT service delivery while maintaining security through ACL rules[span_22](start_span)[span_22](end_span)[span_23](start_span)[span_23](end_span)[span_24](start_span)[span_24](end_span).

---

## ⏱️ Total Project Time Breakdown

| Phase / Milestone | Allocated Duration | Objective |
| :--- | :--- | :--- |
| **Milestone 1** | 40 mins[span_25](start_span)[span_25](end_span) | Flow creation in Flow Designer[span_26](start_span)[span_26](end_span) |
| **Milestone 2** | 11 hrs 40 mins[span_27](start_span)[span_27](end_span) | Linking catalog item to flow[span_28](start_span)[span_28](end_span) |
| **Milestone 3** | 20 mins[span_29](start_span)[span_29](end_span) | Service Catalog item testing[span_30](start_span)[span_30](end_span) |
| **Conclusion** | 10 mins[span_31](start_span)[span_31](end_span) | Project review & documentation[span_32](start_span)[span_32](end_span) |
| **Total Duration** | **12 hrs 50 mins** | Complete pipeline execution |

---

## 📸 Proof of Work & Verification Screenshots


1. `01_user_and_acl_setup.png` – User creation (`sys_user`) and ACL security configurations[span_33](start_span)[span_33](end_span)[span_34](start_span)[span_34](end_span).
2. `02_flow_designer.png` – `Standard Laptop Task Flow` trigger and action steps in Flow Designer[span_35](start_span)[span_35](end_span).
3. `03_flow_assignment.png` – Catalog item mapping to the Flow Designer flow[span_36](start_span)[span_36](end_span).
4. `04_service_catalog_submission.png` – Submitting the Standard Laptop request and verifying task creation assigned to the Hardware team[span_37](start_span)[span_37](end_span)[span_38](start_span)[span_38](end_span).
5.
