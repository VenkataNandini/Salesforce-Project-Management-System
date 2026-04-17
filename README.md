# Salesforce Project Management System

## Project Overview
This project is an end-to-end CRM solution developed on the Salesforce platform to manage project lifecycles. It focuses on automating business processes, ensuring budget compliance, and improving client communication through real-time notifications.

---

## 🛠 Key Features

### 1. Data Modeling & Security
- Created custom objects for **Projects** and **Clients** with a lookup relationship.
- Configured Page Layouts, Compact Layouts, and Record Types for a better user experience.

### 2. Automated Approval Process
- Implemented a multi-step **Approval Process** for project budget management.
- Projects with an estimated expense greater than **₹5,000** are automatically locked and sent to management for review.
- Status transitions are automated based on approval or rejection.

### 3. Flow Automation (Email Alerts)
- Developed **Record-Triggered Flows** to automate communication.
- When a project status is updated to **'Completed'**, the system automatically triggers an Email Alert to the client using a Classic Email Template.

### 4. Custom Reporting (Visualforce)
- Developed a **Visualforce Page** to generate professional Project Summary Reports.
- The page is rendered as a **PDF**, allowing users to download and share project details instantly via a custom button on the record page.

---

## 📂 Repository Contents
- **Visualforce Page:** Contains the source code for the PDF report generation.
- **Screenshots:** Documentation of the Flow Builder logic, Approval Steps, and the final PDF output.
- **Email Templates:** Text templates used for automated client notifications.

---

## 🎓 Learning Outcomes
- Hands-on experience with **Salesforce Flow Builder** and automation logic.
- Understanding of **Declarative Development** (Approvals, Validation Rules).
- Practical application of **Programmatic Development** using Visualforce.
- Experience in end-to-end CRM project implementation.
