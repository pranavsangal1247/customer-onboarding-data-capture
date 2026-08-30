# Customer Onboarding Data Capture 🤖

An end-to-end **UiPath RPA automation** developed to automate customer onboarding data capture from an Excel input file into web-based and desktop CRM applications.

The project demonstrates how RPA can be used to automate repetitive data-entry activities, handle different application interfaces, and improve the consistency and efficiency of the customer onboarding process.

---

## 📌 Project Overview

Customer onboarding often involves capturing customer information from structured input files and entering the same information into business applications.

This project automates that process using **UiPath RPA**.

The automation:

1. Reads customer information from an Excel file.
2. Processes the customer records.
3. Opens the required CRM applications.
4. Captures and enters customer information into the web CRM.
5. Captures and enters customer information into the desktop CRM.
6. Handles application interaction and automation exceptions.
7. Completes the customer onboarding data capture process with minimal manual intervention.

---

## 🎯 Objective

The main objective of this project is to demonstrate an end-to-end RPA solution that can:

- Reduce repetitive manual data-entry activities.
- Improve data-entry consistency.
- Automate customer information processing.
- Interact with both web and desktop applications.
- Handle application-level exceptions.
- Demonstrate reusable UiPath automation techniques.

---

## 🔄 Process Flow

```text
Customer Data
     │
     ▼
Excel Input File
     │
     ▼
UiPath RPA
     │
     ├───────────────┐
     ▼               ▼
 Web CRM        Desktop CRM
     │               │
     └───────┬───────┘
             ▼
   Customer Data Captured
             │
             ▼
    Onboarding Process Completed
