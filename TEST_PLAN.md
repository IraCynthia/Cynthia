# Test Plan - Assignment 3: Test Logging and Reporting with Selenium
**Module:** Development Operations (ITLDO801)  
**Student Name:** Cynthia Iradukunda  
**Target Website:** Portfolio Repository (GitHub Pages)  

## 1. Introduction
This test plan defines the test cases used to verify the core navigation and interactive elements of the personal portfolio website using automated Selenium testing. Each test case includes a unique identifier, description of actions, and expected outcomes, including a negative test to validate error handling and screenshot logging.

## 2. Test Plan Table

| Test ID | What is tested | Steps | Expected Result |
| :--- | :--- | :--- | :--- |
| **TC-01** | Home / Main Page Load | 1. Open the portfolio URL in the browser.<br>2. Wait for the body element to load. | Page loads successfully, and the main document body is fully accessible. |
| **TC-02** | Click "About" Menu | 1. Locate the "About" navigation link.<br>2. Click on the link. | The `#about` section or content becomes visible on the screen. |
| **TC-03** | Click "Resume" Menu | 1. Locate the "Resume" or CV navigation link.<br>2. Click on the link. | Browser navigates to or displays the resume section / URL ends with `#resume`. |
| **TC-04** | Click "Projects" Section | 1. Locate the "Projects" link in the menu.<br>2. Click on it. | The projects list or section is properly displayed to the user. |
| **TC-05** | External Link (GitHub/LinkedIn) | 1. Locate external social/repo profile link.<br>2. Click the link. | The correct external platform URL opens or is targeted properly. |
| **TC-06** | Missing Section (Negative Test) | 1. Attempt to locate a non-existent element/ID (`#non-existent-section-id`).<br>2. Attempt interaction. | Element is not found, test catches the exception, logs a `FAIL` status, and captures an automated failure screenshot. |
