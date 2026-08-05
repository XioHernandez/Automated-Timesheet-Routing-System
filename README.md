# Automated-Timesheet-Routing-System

## Overview

This project automates the collection, routing, 
and tracking of employee timesheet correction 
requests.

Supervisors submit correction requests 
through a centralized Microsoft Form. Power 
Automate evaluates the selected Area Supervisor 
and automatically routes the submission to the 
corresponding Excel worksheet + Tab for tracking 
and processing.

## Technologies Used

- Microsoft Forms
- Power Automate
- Excel Online (Business)
- Microsoft 365
- Workflow Automation
- Conditional Logic
- Data Routing

---

## Problem

Timesheet correction requests were collected 
manually and required additional effort to 
organize by Supervisor.

Challenges:

- Manual sorting of requests
- Duplicate data entry
- Increased processing time
- Difficulty tracking requests by supervisor
- Higher risk of human error

---

## Solution

A Microsoft Form intake solution was created
to collect payroll adjustment requests.

### Workflow Architecture with screenshots:

---

### Microsoft Form
1. Microsoft Forms is accessed
![Description of screenshot](screenshots/form-overview.png)

### Supervisor Selection
2. User selects an Area Supervisor (self).
![Description of screenshot](screenshots/supervisor-selection.png)

### Branching Logic
3. Form's branching directs users to the appropriate
   section (their cluster of schools).
![Description of screenshot](screenshots/branching-logic.png)

### Adjustment Form Fields
4. User completes the adjustment request.
![Description of screenshot](screenshots/supervisor-adjustment.png)

### Power Automate Flow
5. Power Automate retrieves the form response.

![Description of screenshot](screenshots/power-automate-flow.png)

### Switch Routing Logic
6. A Switch condition evaluates the selected Area Supervisor.
![Description of screenshot](screenshots/switch-logic.png)

### Data Mapping
7. Microsoft Forms responses are mapped to Excel Online columns
using dynamic content.
![Description of screenshot](screenshots/excel-routing.png)

### Successful Execution
8. Power Automate runs successfully automatically when a 
new request is submitted.
![Description of screenshot](screenshots/successful-run.png)

### Final Output
9. Data is automatically written to the correct 
Excel table + Tab.
![Description of screenshot](screenshots/final-data-output.png)
