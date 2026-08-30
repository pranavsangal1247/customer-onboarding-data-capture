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

🏗️ Automation Architecture

The project consists of a main UiPath workflow that coordinates separate automation workflows for web and desktop applications.

                    Main.xaml
                       │
          ┌────────────┴────────────┐
          │                         │
          ▼                         ▼
WebDataCapturing.xaml    DesktopDateCapturing.xaml
          │                         │
          ▼                         ▼
       Web CRM                 Desktop CRM
Main Components
Component	Purpose
Main.xaml	Main workflow that controls the overall automation
WebDataCapturing.xaml	Automates customer data capture in the web CRM
DesktopDateCapturing.xaml	Automates customer data capture in the desktop CRM
Customer_Data.xlsx	Sample customer input data
project.json	UiPath project configuration
🛠️ Technologies & Tools
UiPath Studio
RPA (Robotic Process Automation)
Microsoft Excel
Web UI Automation
Desktop UI Automation
Selectors
Computer Vision
DataTables
Exception Handling
⚙️ Key Automation Features
1. Excel Data Processing

The automation reads customer information from the provided Excel input file and processes the records for downstream automation.

2. Web Application Automation

UiPath interacts with the web-based CRM application to capture and enter customer information.

3. Desktop Application Automation

The automation also interacts with a desktop CRM application to complete the required customer data-entry activities.

4. UI Selectors

Selectors are used to identify and interact with application elements reliably wherever applicable.

5. Computer Vision

Computer Vision techniques are used where traditional UI element identification may not be sufficient.

6. Exception Handling

The workflow incorporates error-handling mechanisms to improve automation reliability and manage unexpected situations during execution.

📂 Repository Structure
customer-onboarding-data-capture/
│
├── README.md
│
├── Main.xaml
├── WebDataCapturing.xaml
├── DesktopDateCapturing.xaml
├── project.json
├── project.uiproj
├── entry-points.json
│
└── Customer_Data.xlsx

The desktop CRM application used as a target application for the automation is not included in this repository because it is a third-party/demo application provided as part of the learning environment.

📊 Input Data

The automation uses an Excel file containing sample customer information.

The data is used as the source for the automated customer onboarding process.

Note: The Excel file included in this repository contains dummy/sample data and does not contain real customer information.

🎥 Demo

A demonstration video of the automation can be added here.

Coming soon

The demo will demonstrate the complete flow from Excel input through automated customer data capture.

📸 Screenshots

Screenshots demonstrating the UiPath workflow, web automation, desktop automation, and final results can be added here.

🧠 Skills Demonstrated

This project demonstrates practical experience with:

Robotic Process Automation
UiPath Studio
Workflow design
Excel automation
Web automation
Desktop application automation
UI selectors
Computer Vision
DataTables
Exception handling
Debugging and troubleshooting
End-to-end automation design
🚀 Learning Outcome

This project provided practical experience in designing and implementing an end-to-end RPA workflow involving multiple applications and data sources.

It demonstrates how UiPath can be used to automate repetitive business processes while maintaining structured workflows and handling application-level challenges.

⚠️ Disclaimer

This project was developed as part of an RPA learning project using a demo CRM application.

The CRM application itself is not included in this repository because it is a third-party application.

The included customer data is dummy/sample data created for demonstration purposes only.
