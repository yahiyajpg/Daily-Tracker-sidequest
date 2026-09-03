# PMO Tracker

A lightweight, browser-based Project Management Office (PMO) workspace designed to keep daily work, projects, deliverables, risks, requests, and documentation organized in one place.

## Overview

PMO Tracker provides a centralized workspace for managing multiple projects and tracking the work associated with them.

The application allows users to:

* Manage multiple projects
* Track milestones and deadlines
* Manage deliverables and work items
* Track support and service requests
* Maintain internal documentation
* Monitor Risks, Assumptions, Issues, and Dependencies (RAID)
* View a consolidated dashboard across all projects
* Review upcoming and overdue work in My Day
* Capture quick reminders using Sticky Notes

All data is managed locally in the browser using an in-browser SQLite database.

## Features

### My Day

The My Day view provides a consolidated view of work that requires attention across all projects.

It displays:

* Upcoming milestones
* Upcoming work items
* Open support and service requests
* Overdue milestones
* Open RAID items
* Active project count

### Dashboard

The Dashboard provides a high-level roll-up across the PMO workspace.

It includes:

* Open versus total items by tracker
* RAID item breakdown
* Projects by category
* Total project count
* Total sticky notes

### Projects

Users can create and manage multiple projects.

Projects can be categorized as:

* Strategy
* Delivery
* Operations
* Reporting

Each project includes its own workspace for tracking milestones, work items, requests, documentation, and RAID items.

## Project Trackers

### Milestones

Track key project milestones, including:

* Milestone
* Due date
* Owner
* Status

Available statuses:

* Not Started
* In Progress
* At Risk
* Done

### Deliverables / Work Items

Track project tasks and deliverables.

Fields include:

* Item
* Type
* Owner
* Due date
* Status

Supported work item types:

* Feature
* Report
* Configuration
* Training
* Migration

### Support & Service Requests

Track requests and operational issues related to projects.

Fields include:

* Request
* Type
* Priority
* Requester
* Date
* Status

Request types include:

* Support
* Service Request
* Incident

Priority levels include:

* Low
* Medium
* High
* Critical

### Internal Documentation

Maintain references to important project documentation.

Documentation categories include:

* SOP
* Design
* Meeting Notes
* Policy
* Guide

Each document can include an owner, updated date, and optional link.

### RAID Log

Track project Risks, Assumptions, Issues, and Dependencies.

Each entry includes:

* Type
* Description
* Owner
* Impact
* Status

RAID categories include:

* Risk
* Assumption
* Issue
* Dependency

## Sticky Notes

The Sticky Notes section allows users to capture quick reminders, ideas, and informal notes that do not require a full project tracker entry.

Users can:

* Create notes
* Select different note colors
* Delete notes
* Capture reminders and ideas quickly

## Data Storage

PMO Tracker uses SQLite through sql.js and stores data locally in the browser.

The application automatically saves changes, allowing users to continue managing their workspace without requiring a traditional backend database.

## Technology Stack

* HTML
* CSS
* JavaScript
* SQLite
* sql.js

## Application Structure

```text
PMO Tracker
│
├── My Day
├── Dashboard
├── Sticky Notes
│
└── Projects
    ├── Overview
    ├── Milestones
    ├── Deliverables / Work Items
    ├── Support & Service Requests
    ├── Internal Documentation
    └── RAID Log
```

## Getting Started

1. Save or download the application HTML file.
2. Open the file in a modern web browser.
3. Create a project.
4. Add milestones, work items, requests, documentation, and RAID entries.
5. Use My Day and Dashboard to review priorities across projects.

## Use Cases

PMO Tracker can be used for:

* Project portfolio management
* Implementation tracking
* Client onboarding
* Migration projects
* Go-live readiness tracking
* Internal PMO operations
* Risk and issue management
* Cross-functional project coordination

## Future Enhancements

Potential future enhancements include:

* User authentication
* Cloud-based data storage
* Team collaboration
* Search and filtering
* Export to Excel or CSV
* Automated reminders
* Email notifications
* Advanced reporting
* Gantt charts and project timelines
* File attachments
* Role-based access
* Integration with external project management tools

## Author

Yahiya M//////

## License

This project is intended for personal and internal PMO productivity use.
