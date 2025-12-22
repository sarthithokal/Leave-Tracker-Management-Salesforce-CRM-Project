# Leave Tracker Management App – Salesforce CRM

##  Project Overview
The **Leave Tracker Management App** is a Salesforce CRM-based solution developed to streamline how organizations track employee leave requests, balances, and approvals. By leveraging **Apex** and **LWC**, this project automates the entire leave lifecycle, providing real-time insights into workforce availability and leave trends.



##  Tech Stack
* **Platform:** Salesforce CRM
* **Development:** Apex (Triggers, Batch, Schedulable), Lightning Web Components (LWC)
* **Automation:** Flows, Validation Rules, Approval Processes
* **Analytics:** Salesforce Reports & Dashboards



##  The Problem
Many organizations struggle with fragmented leave management systems characterized by:
* **Manual Tracking:** Leave applications handled via emails or spreadsheets.
* **Information Silos:** No centralized view of real-time leave balances or history.
* **Reporting Gaps:** Difficulty for HR to generate trends on absenteeism or pending approvals.
* **Lack of Alerts:** Managers often miss pending requests due to a lack of automated notifications.



##  The Solution
A digital-first, automated system built on Salesforce:
* **Custom Data Architecture:** Linked Employee and Leave objects for 100% data integrity.
* **Intelligent Automation:** **Apex Triggers** prevent overlapping leaves, while **Batch Apex** auto-calculates monthly accruals.
* **Modern UI:** A custom **Lightning Web Component (LWC)** for a user-friendly application experience.
* **Real-time Analytics:** Custom **Dashboards** providing HR and Managers with visibility into departmental leave trends.



##  Technical Implementation (10 Phases)
1.  **Requirements & Analysis:** Mapped the leave application and approval workflow.
2.  **Org Setup:** Configured Roles, Profiles, and Permission Sets for security.
3.  **Data Modeling:** Established Master-Detail/Lookup relationships between Employees and Policies.
4.  **Admin Automation:** Implemented Validation Rules and Email Alerts.
5.  **Apex Development:** Coded Triggers for overlap prevention and Scheduled Apex for summaries.
6.  **UI/UX:** Built a dedicated "Leave Tracker" App using Lightning App Builder.
7.  **Integrations:** Set up REST/SOAP callout structures for external payroll potential.
8.  **Data Management:** Performed bulk data migration using **Data Loader**.
9.  **Reporting & Security:** Built dynamic dashboards and enforced **Field-Level Security**.
10. **Final Deployment:** Successfully demoed the end-to-end approval flow and insights.



##  Key Metrics & Impact
* **Efficiency:** Reduced manual intervention through automated balance updates.
* **Transparency:** Employees gain real-time visibility into their own leave history.
* **Data Accuracy:** Prevented redundant records using Salesforce Duplicate Rules.
* **Decision Support:** Managers can now make staffing decisions based on live departmental summaries.



##  Stakeholders
* **Employees:** Submit requests and track balances.
* **Managers:** Review requests and monitor team availability.
* **HR/Admins:** Manage global policies and generate compliance reports.
