# PMO Tracker

A lightweight, browser-based Project Management Office (PMO) workspace for managing projects, milestones, work items, requests, documentation, RAID items, and day-to-day project activities in one place.

## Overview

PMO Tracker provides a centralized workspace for managing multiple projects and the work associated with them.

The application is designed to give a PMO or project team a single place to:

* Manage multiple projects
* Track milestones and deadlines
* Manage deliverables and work items
* Track support and service requests
* Maintain project documentation
* Monitor Risks, Assumptions, Issues, and Dependencies (RAID)
* Review project activity through a consolidated dashboard
* Organize upcoming and overdue work through My Day
* Capture quick reminders using Sticky Notes
* Customize project categories, statuses, priorities, and tracker types through Settings

PMO Tracker runs entirely in the browser and uses an in-browser SQLite database for local data storage.

## Core Features

### My Day

My Day provides a consolidated view of work requiring attention across the PMO workspace.

It includes:

* Upcoming milestones
* Upcoming work items
* Open support and service requests
* Overdue milestones
* Open RAID items
* Active project count

This provides a quick starting point for reviewing current priorities.

### Dashboard

The Dashboard provides a high-level overview of the PMO workspace.

It includes:

* Open and total items across project trackers
* RAID breakdown
* Projects by category
* Project counts
* Sticky note counts
* Overall project activity

### Projects

Projects are the central part of the workspace.

Each project can contain its own:

* Overview
* Milestones
* Work Items
* Support & Service Requests
* Internal Documentation
* RAID Log

Projects can also be:

* Edited
* Duplicated
* Favorited
* Archived
* Restored
* Deleted

Project information can include:

* Project name
* Description
* Category
* Owner
* Status
* Priority
* Start date
* Target date
* Client
* Project color

## Project Trackers

### Milestones

Track important project milestones and deadlines.

Each milestone can include:

* Milestone name
* Due date
* Owner
* Status
* Notes

### Work Items

Track project deliverables, tasks, and other pieces of work.

Each work item can include:

* Item name
* Type
* Owner
* Due date
* Status
* Notes

Work item types can be customized through Settings.

### Support & Service Requests

Track requests and operational issues associated with projects.

Each request can include:

* Request
* Type
* Priority
* Requester
* Date
* Status
* Notes

Request types and priorities can be customized through Settings.

### Internal Documentation

Maintain references to important project documentation.

Documentation entries can include:

* Document name
* Category
* Owner
* Updated date
* Link
* Notes

Document categories can be customized through Settings.

### RAID Log

Track:

* Risks
* Assumptions
* Issues
* Dependencies

Each RAID entry can include:

* Type
* Description
* Owner
* Impact
* Status
* Notes

RAID types and impact levels can be customized through Settings.

## Settings

Settings allows the workspace to be configured without changing the application code.

Users can manage their own lists for:

* Project categories
* Project statuses
* Project priorities
* Work item types
* Request types
* RAID types
* RAID impacts
* Documentation categories

Workspace information such as the workspace name and user name can also be customized.

## Editing & Organization

PMO Tracker supports editing directly within the workspace.

* Click a tracker row to open its edit panel
* Double-click a title for quick renaming
* Edit project information through the project menu
* Duplicate projects when a similar structure is needed
* Archive projects without permanently deleting them
* Restore archived projects when needed
* Delete projects with a confirmation step

## Sticky Notes

Sticky Notes provides a lightweight space for reminders, ideas, and information that does not require a formal project tracker entry.

Users can:

* Create notes
* Customize note colors
* Edit notes
* Delete notes

## Read-Only Mode

PMO Tracker supports a read-only experience for sharing the workspace with visitors.

In read-only mode, visitors can browse the available project information and dashboards without access to editing or destructive actions.

This makes the application suitable for showcasing the workspace or sharing project information without allowing visitors to modify it.

## Data Storage

PMO Tracker uses **SQLite through sql.js** to manage application data directly in the browser.

Data is stored locally, so the application does not require a traditional backend database or server-side application.

Because data is browser-local, different browsers or devices will have separate data stores unless a future cloud-backed storage layer is introduced.

## Technology Stack

* **HTML** - Application structure
* **CSS** - Layout and styling
* **JavaScript** - Application logic and interactions
* **SQLite** - Local relational data model
* **sql.js** - SQLite running inside the browser
* **Google Fonts** - Application typography

## Application Structure

```text
PMO Tracker
│
├── My Day
├── Dashboard
├── Sticky Notes
├── Settings
│
└── Projects
    │
    ├── Project Overview
    ├── Milestones
    ├── Work Items
    ├── Support & Service Requests
    ├── Internal Documentation
    └── RAID Log
```

## Getting Started

PMO Tracker is a client-side application and does not require a backend setup.

1. Clone or download the repository.
2. Open `index.html` in a modern web browser.
3. Create or configure your workspace.
4. Create a project.
5. Add milestones, work items, requests, documentation, and RAID entries.
6. Use My Day and Dashboard to review activity across projects.
7. Use Settings to customize the workspace and available tracker options.

For local development, the application can also be served through a simple local web server.

## Use Cases

PMO Tracker can be used for:

* Project portfolio management
* Implementation tracking
* Client onboarding
* Migration projects
* Go-live readiness
* Internal PMO operations
* Risk and issue management
* Cross-functional project coordination
* Project documentation management
* Operational work tracking

## Project Status

PMO Tracker is an evolving side project focused on experimenting with a lightweight, browser-based approach to PMO and project work management.

## Links

**Live Application:** [Add live app link]

**Repository:** [Add GitHub repository link]

## Author

**Yahiya M.**

## License

This project is intended for personal and internal PMO productivity use.
