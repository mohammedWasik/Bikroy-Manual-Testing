
# [Bikroy Test Cases Repository](https://docs.google.com/spreadsheets/d/1Y6DNf-YYh0A3VhoscEBhIk17ZCibKgCH/edit?usp=sharing&ouid=114466841894240379307&rtpof=true&sd=true)

## Project Details

-   **Project Name:** Bikroy
    
-   **Reference Document:** Functional Requirement Specification (FRS)
    
-   **Created By:** Mohammed Wasik
    
-   **Creation Date:** 28/02/2025
    
-   **Approval Date:** TBD
    

## Overview

This repository contains the test cases for Bikroy.com, a leading online marketplace in Bangladesh. The test plan is designed to ensure core functionalities work as expected and provide users with a seamless experience. The test plan includes functional, UI, security, and compatibility testing.

## Test Plan Summary

-   **Test Plan ID:** TP_Bikroy_001
    
-   **Scope:**
    
    -   User authentication (Signup, Login, Logout, Forgot Password)
        
    -   Search functionality
        
    -   Chat feature
        
    -   Posting and managing ads
        
    -   Landing page responsiveness
        
    -   Cross-browser compatibility
        
    -   Performance testing
        
    -   Backend database tuning
        
-   **Testing Types:**
    
    -   Functional Testing
        
    -   UI/UX Testing
        
    -   Compatibility Testing
        
    -   Security Testing
        
-   **Test Environment:**
    
    -   **Devices:** Desktop, Laptop, Mobile
        
    -   **Browsers:** Chrome, Firefox, Safari, Edge
        
    -   **Operating Systems:** Windows, macOS, Android, iOS
        
    -   **Testing Tools:** Selenium, Postman, BrowserStack
        

## Test Scenarios
-   **Signup (P0):** Validate registration, error handling, verification, and social login.
-   **Login (P0):** Verify valid/invalid logins, account lockout, and social login.
-   **Logout (P0):** Verify successful logout, session expiry, and redirection.
-   **Forgot Password (P1):** Verify reset process via OTP/email and password validation.
-   **Search (P0):** Check keyword search, filters, sorting, and suggestions.
-   **Chat (P1):** Validate real-time messaging, notifications, and unread indicators.
-   **Ad (P0):** Verify ad posting, editing, deleting, and image uploads.
-   **Header (P1):** Verify navigation links and responsiveness.
-   **Footer (P1):** Verify footer links and accessibility.
-   **Landing Page (P1):** Check UI, responsiveness, and loading speed.
-   **BikroyJOBS Header (P2):** Validate navigation and drop-downs.
-   **BikroyJOBS Footer (P2):** Validate Test links and copyright details.
-   **Account Deleteion (P1):** Validate BikroyJOBS Account Deletion Functionality.

## Defect Management

-   **Bug Tracking Tool:** JIRA
    
-   **Severity Levels:**
    
    -   Critical (P0)
        
    -   High (P1)
        
    -   Medium (P2)
        
    -   Low (P3)
        
-   **Defect Review Process:**
    
    -   Regular defect triage meetings will be conducted
        

## Test Execution Schedule

-   **Test Planning:** Week 1
    
-   **Test Case Design:** Week 2
    
-   **Test Execution:** Weeks 3-4
    
-   **Defect Fixing & Regression Testing:** Week 5
    

## Risk Mitigation Table

| **Risk**                         | **Mitigation Strategy**                                    |
|----------------------------------|------------------------------------------------------------|
| Unstable test environment        | Regular sync with dev team                                 |
| Cross-browser inconsistencies    | Use automated tools like BrowserStack                      |
| Delays in test execution         | Prioritize critical test cases (P0, P1)                    |


## Roles & Responsibilities

-   **Test Engineer:** Execute test cases, report defects
    
-   **Developer:** Fix defects and provide stable builds
    
-   **Test Lead:** Review test cases, oversee execution
    
-   **Product Owner:** Approve test results before UAT
    

## Approval & Sign-off

-   **Test Plan Approval:** Required from Project Manager/QA Lead
    
-   **Sign-off:** Required from Development, QA, and Product teams
