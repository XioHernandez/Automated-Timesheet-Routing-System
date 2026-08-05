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

A Microsoft Forms intake solution was developed
to collect payroll adjustment requests.

The workflow:

1. User selects an Area Supervisor.
2. Forms branching directs users to the appropriate
   section (their cluster of schools).
3. User completes the adjustment request.
4. Power Automate retrieves the form response.
5. A Switch condition evaluates the selected Area Supervisor.
6. Data is automatically written to the correct Excel table + Tab.
7. Requests are then organized by supervisor.

---

## Screenshots

### Solution Overview

### Form Overview
![Description of screenshot](screenshots/form-overview.png)


### Supervisor Selection

### Branching Logic

### Adjustment Form Fields

### Power Automate Flow

### Switch Routing Logic

### Data Mapping

### Successful Execution

### Supervisor Routing Output

### Final Output
