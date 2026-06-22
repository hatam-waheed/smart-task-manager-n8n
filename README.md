# AI Smart Task Manager

## Overview

AI Smart Task Manager is an intelligent workflow built with n8n that automatically analyzes incoming tasks, assigns priority levels, identifies the responsible department, and stores all information inside Google Sheets.

---

## Features

✅ Task Submission Form

✅ Automatic Task Logging

✅ AI Priority Classification

✅ Department Classification

✅ Parallel AI Processing

✅ Google Sheets Integration

---

## Workflow

### Step 1: Task Submission

Users submit:

* Name
* Task Title
* Task Description

### Step 2: Initial Storage

The submitted information is saved to Google Sheets.

### Step 3: Priority Classification

An AI Agent powered by Groq analyzes the task and assigns:

* HIGH
* MEDIUM
* LOW

### Step 4: Department Classification

A second AI Agent categorizes the task into:

* IT
* HR
* Finance
* Marketing
* Sales
* Support
* Operations
* General

### Step 5: Spreadsheet Update

The workflow automatically updates the corresponding row with:

* Priority Level
* Department

---

## Tech Stack

* n8n
* Groq LLM
* Google Sheets
* AI Agents

---

## Use Cases

* Helpdesk ticket management
* Internal company task assignment
* Team workload organization
* Business process automation

---

## Future Improvements

* Email notifications
* Slack integration
* Deadline prediction
* Task reminders
* Team dashboards

---

## Author

Hattam Waheed
