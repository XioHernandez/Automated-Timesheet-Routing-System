# Automated-Timesheet-Routing-System

## Overview

This project automates the collection, routing, 
and tracking of employee timesheet correction 
requests using Microsoft Forms, Power Automate,
and Excel Online.

Area Supervisors submit correction requests 
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
organize by Area Supervisor.

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

The workflow:

1. User selects an Area Supervisor (self).
2. Form's branching directs users to the appropriate
   section (their cluster of schools).
3. User completes the adjustment request.
4. Power Automate retrieves the form response.
5. A Switch condition evaluates the selected Area Supervisor.
6. Data is automatically written to the correct Excel table + Tab.
7. Requests are then organized by supervisor.

---

## Solution Overview (Screenshots)

### Form Overview
![Description of screenshot](screenshots/form-overview.png)

### Supervisor Selection
![Description of screenshot](screenshots/supervisor-selection.png)

### Branching Logic
![Description of screenshot](screenshots/branching-logic.png)

### Adjustment Form Fields
![Description of screenshot](screenshots/supervisor-adjustment.png)

### Power Automate Flow
![Description of screenshot](screenshots/power-automate-flow.png)

### Switch Routing Logic
![Description of screenshot](screenshots/switch-logic.png)

### Data Mapping
![Description of screenshot](screenshots/excel-routing.png)

### Successful Execution
![Description of screenshot](screenshots/successful-run.png)

### Final Output
![Description of screenshot](screenshots/final-data-output.png)
