# Streamlining-IT-Procurement-Automating-Standard-Laptop-Orders-With-Flow-Designer
ServiceNow ACL &amp; User Administration Project 
# ServiceNow Automation & Security Configuration

## 📌 Project Overview
This project demonstrates complete request fulfillment automation and Access Control List (ACL) security setup in ServiceNow as part of the Naan Mudhalvan SkillWallet program[span_0](start_span)[span_0](end_span)[span_1](start_span)[span_1](end_span). It covers user management, ACL security controls, Flow Designer automation, and Service Catalog integration[span_2](start_span)[span_2](end_span)[span_3](start_span)[span_3](end_span)[span_4](start_span)[span_4](end_span)[span_5](start_span)[span_5](end_span).

---

## 🛠️ Complete Project Breakdown & Milestones

### **Image 1 & 2: User Administration & Access Control (ACLs)**
* **User & Role Administration:** Created and configured users (e.g., `EEE User`) in the `sys_user` table[span_6](start_span)[span_6](end_span)[span_7](start_span)[span_7](end_span).
* **ACL Security Setup:** Elevated permissions to `security_admin` and implemented CRUD-level Access Control Rules (`READ`, `CREATE`, `WRITE`, `DELETE`) to restrict table and record access[span_8](start_span)[span_8](end_span).

### **Image 3 (Milestone 1): Flow Implementation**
* **Objective:** Design and configure the `Standard Laptop Task Flow` in Flow Designer[span_9](start_span)[span_9](end_span).
* **Functionality:** Listens for request approvals and automatically creates a Catalog Task assigned to the **Hardware** team for configuration[span_10](start_span)[span_10](end_span).

### **Image 4 (Milestone 2): Flow Assignment**
* **Objective:** Link the `Standard Laptop` catalog item directly to the `Standard Laptop Task Flow`[span_11](start_span)[span_11](end_span).
* **Functionality:** Ensures the automated flow executes seamlessly whenever a catalog request is submitted[span_12](start_span)[span_12](end_span).

### **Image 5 (Milestone 3): Service Catalog Integration**
* **Objective:** Configure the `Standard Laptop` catalog item in the Service Catalog[span_13](start_span)[span_13](end_span).
* **Functionality:** Allows users to submit laptop requests, triggering automated approval workflows and routing tasks to the **Hardware** team[span_14](start_span)[span_14](end_span)[span_15](start_span)[span_15](end_span).

---

## 💡 Conclusion & Key Benefits
By automating the standard laptop procurement process with ServiceNow's **Flow Designer** and securing record permissions via **ACLs**, this project effectively addresses operational inefficiencies and eliminates manual task creation[span_16](start_span)[span_16](end_span)[span_17](start_span)[span_17](end_span)[span_18](start_span)[span_18](end_span). The streamlined workflow ensures timely laptop configuration, reduces wait times, and optimizes resource allocation across the IT department[span_19](start_span)[span_19](end_span)[span_20](start_span)[span_20](end_span).

---

## 📸 Screenshots & Verification
*(Upload your screenshots to a `screenshots/` directory in this GitHub repository)*

* `01_user_and_acl_setup.png` – User administration and ACL rules[span_21](start_span)[span_21](end_span)[span_22](start_span)[span_22](end_span).
* `02_flow_designer_config.png` – Standard Laptop Task Flow configuration[span_23](start_span)[span_23](end_span).
* `03_flow_assignment.png` – Linking flow to the catalog item[span_24](start_span)[span_24](end_span).
* `04_service_catalog_test.png` – Request submission and task generation[span_25](start_span)[span_25](end_span)[span_26](start_span)[span_26](end_span).
*
