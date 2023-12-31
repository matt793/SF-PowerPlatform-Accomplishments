# This Year's Power Platform Projects 

## Introduction
> **Spencer Fane Law Firm**  
> Role: Power Platform Developer  
> Focus: Digital Transformation with Power Apps, and Process Automation with Power Automate

---

## Daily personal goal with this platform
- it's been a personal goal of mine to improve the functionality of how the firm gets work done. Automation is critical to me and it is necessary to stay competitive as an organization.
- it's also been a personal goal of mine to evangelize the power platform to help others create and make their projects. I am very focused on achieving automations but at the same time I don't believe in gatekeeping and I have shared my knowledge with others so that they could also finish their projects.

---

## Projects Overview
Each project showcases unique solutions and innovations in the Power Platform space.

---

### 🌟 Project 1: Email Access Management Application and Workflow
- **Objective:** Streamline email permission granting process.
- **Key Features:** User-friendly app interface, Multiple access level selections.
- **Workflow:** Automated emails via Power Automate, PowerShell integration.
- **Impact:** Efficiency and control in email access management.
- **Gallery:**  
  ![Email Access UI](/Images/1EmailAccessUI.png)  
  ![Email Access Flow](/Images/EmailAccessFlow.png)

---

### 🌟 Project 2: Active Directory Group Approval Automation
- **Objective:** Simplify Active Directory group memberships.
- **Application Features:** List/descriptions of AD groups, User account selection.
- **Approval Process:** IT representative approval, PowerShell scripting.
- **Impact:** Enhanced group management efficiency and security.
- **Gallery:**  
  ![AD Access](/Images/AD_UI.png)  
  ![AD Flow](/Images/AD_Flow.png)

---

### 🌟 Project 3: New Hire Orientation Scheduler
- **Objective:** Streamline scheduling for new employee orientation.
- **Application Features:** Scheduling tool for trainers, Orientation meeting setup.
- **Automation:** Power Automate for meeting scheduling.
- **Impact:** Improved onboarding experience and efficiency.
- **Gallery:**  
  ![Onboarding UI](/Images/OnboardUI.png)  
  ![Onboarding Flow](/Images/OnboardFlow.png)

---

### 🌟 Project 4: E3 License Utilization API
- **Objective:** Monitor and manage E3 license allocation.
- **API Integration:** Azure report generation.
- **Data Handling:** Advanced JSON parsing.
- **Impact:** Improved license management and cost-efficiency.
- **Gallery:**  
  ![API Flow](/Images/API_Flow.png)  
  ![API Email](/Images/API_Email.png)

---

### 🌟 Project 5: Power Virtual Agents Chatbot
- **Objective:** Enhance IT support with a virtual assistant.
- **Key Features:** Personalized interactions, Diverse IT support topics.
- **PVA Topics:**
  1. Create a Ticket Flow
  2. Email Access App Connection
  3. Send KB Information to User
  4. AR Holding App Connection
  5. Denver Printer Information
  6. Helping Jennifer's Software List Topic
  7. Single Sign-On API for User Recognition
- **Integration:** Backend automation via Power Automate.
- **Impact:** Enhanced IT support and user satisfaction.
- **Gallery:**  
  ![PVA ChatBot](/Images/ChatBot.png)

---

### 🌟 Project 6: Accounts Receivable Hold Management Automation
- **Objective:** Improve management of client case AR holds.
- **Application Features:** AR hold release request facilitation.
- **Workflow:** Senior admin approval via Power Automate.
- **Impact:** Improved financial management and operational efficiency.
- **Gallery:**  
  ![AR Hold UI](/Images/AR_UI.png)  
  ![AR_Flow](/Images/AR_Flow.png)

---

### 🌟 Project 7: IT Technical Assessment for Office Visits
- **Objective:** Efficient IT technical assessments for resource allocation.
- **Application Features:** Comprehensive data collection via questionnaire.
- **Data Utilization:** Resource planning and ticket resolution.
- **Impact:** Informed decision-making and resource distribution.
- **Gallery:**  
  ![Office UI](/Images/Office_UI.png)  
  ![Office Teams Message](/Images/Office_Message.png)

---

### 🌟 Project 8: Onboarding Schedule Report Automation
- **Objective:** Enhance HR's onboarding schedule review process.
- **Application Features:** Email and date range input for schedule compilation.
- **Automation:** Event extraction and email preparation via Power Automate.
- **Impact:** Comprehensive schedules for HR, efficient new hire transitions.
- **Gallery:**  
  ![Report Flow](/Images/GRAB_Flow.png)

---

### 🌟 Project 9: Azure Policy Country Approval Automation

- **Objective:** Facilitate the secure and compliant addition of new countries to the Azure AD approved policy list.
- **Key Features:** 
  - Streamlined approval process for new country additions.
  - Seamless PowerShell script execution for Azure AD updates.
  - Intuitive Power App interface for submission of country additions.
  - Calendar Tracking: You can now monitor dates approved with the built in UI calendar.
- **Workflow:** 
  - Power App initiates a country addition request.
  - Power Automate triggers an approval process, sends notifications to approvers, and awaits their decision.
  - Once approved, a PowerShell script is executed to update the Azure AD policy with the new country codes.
- **Impact:** Ensures timely updates to access policies, reduces administrative workload, and maintains compliance with organizational security standards.
- **Gallery:**  
  ![Policy Approval UI](/Images/LocationApprovalUI1.png)  
  ![Policy Approval Flow](/Images/LocationApprovalFlow.png)
  ![Policy Approval UI Calendar](/Images/LocationApprovalUI2.png)    

In this project, Power Automate orchestrates the addition of new countries to Azure AD's policy list through a managed approval process. The flow initiates when a country addition request is made, setting up variables for user details and policy information. An approval email is dispatched, and upon affirmative response, the automation schedules the update using the start date provided. It retrieves and compiles necessary data from SharePoint, where policy details are maintained, and uses a PowerShell script to update Azure AD policy accordingly. This script, leveraging Microsoft Graph, automates the authorization and update process, ensuring secure and efficient policy management.

---
