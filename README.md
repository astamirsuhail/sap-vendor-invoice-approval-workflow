# Vendor Invoice Approval Workflow using SAP Build Process Automation

![SAP](https://img.shields.io/badge/SAP-BTP-blue)
![Automation](https://img.shields.io/badge/SAP-Build%20Process%20Automation-success)
![Status](https://img.shields.io/badge/Project-Deployed-brightgreen)

## Overview

This project demonstrates an enterprise-grade Vendor Invoice Approval Workflow built using **SAP Build Process Automation** on **SAP Business Technology Platform (SAP BTP)**.

The workflow automates invoice approvals by routing requests to different approvers according to invoice amount using a Decision Table.

---

# Business Problem

Manual invoice approvals are:

- Slow
- Error-prone
- Difficult to track
- Require manual routing

This solution automates the approval process using SAP's Low-Code platform.

---

# Workflow

Vendor submits invoice

↓

Decision Table

↓

Manager Approval (≤ 50,000)

OR

Finance Approval (≤ 200,000)

OR

Director Approval (> 200,000)

↓

Workflow Ends

---

# Business Rules

| Invoice Amount | Approval |
|---------------|----------|
| ≤ 50,000 | Manager |
| ≤ 200,000 | Finance |
| > 200,000 | Director |

---

# Technologies Used

- SAP BTP
- SAP Build Process Automation
- SAP Forms
- SAP Decision Tables
- Workflow Automation
- Business Rules

---

# Features

- Vendor Invoice Request Form
- Dynamic Approval Routing
- Decision Table
- Multi-Level Approval Workflow
- Rule-Based Processing
- Low-Code Automation
- SAP Build Deployment

---

# Screenshots

## Workflow

![Workflow](screenshots/workflow.png)

---

## Vendor Request Form

![Form](screenshots/vendor-request-form.png)

---

## Decision Table

![Decision](screenshots/decision-table.png)

---

## Approval Rule

![Rule](screenshots/approval-rule.png)

---

## Deployment

![Deployment](screenshots/deployment.png)

---

# Project Learnings

Through this project I learned:

- SAP Build Process Automation
- SAP BTP Project Lifecycle
- Workflow Design
- Forms Development
- Decision Tables
- Business Rules
- Release Management
- Deployment
- Version Management

---

# Skills Demonstrated

- Business Process Automation
- Enterprise Workflow Design
- SAP BTP
- SAP BPA
- Decision Management
- Process Modeling
- Low-Code Development

---

# Future Improvements

- SAP S/4HANA Integration
- Email Notifications
- Purchase Order Validation
- Vendor Master Validation
- Approval History Dashboard
- Analytics using SAP Build Apps

---

## Author

**Aamir Suhail**

PGDM | Business Analytics | SAP Build Process Automation | Power BI | Business Analyst

LinkedIn:
(www.linkedin.com/in/astamirsuhail)

GitHub:
(Add your GitHub Profile URL)
