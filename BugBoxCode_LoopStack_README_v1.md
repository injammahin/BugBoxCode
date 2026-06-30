# BugBoxCode LoopStack App v1

BugBoxCode is a fully offline bug tracker for solo developers and freelancers. The application runs directly from a single HTML file and stores all bug data in the browser using localStorage.

## Included Files

- `BugBoxCode_LoopStack_App_v1.html` - Complete single-file offline bug tracker with inline CSS and JavaScript.
- `BugBoxCode_LoopStack_README_v1.md` - Setup and usage guide.
- `Logo.png` - Application logo asset.

## Setup

1. Download or unzip the project package.
2. Open `BugBoxCode_LoopStack_App_v1.html` directly in a current version of Chrome, Firefox, or Edge.
3. No backend, npm, build tool, login, or server setup is required.

## Features

- Full bug CRUD with all 8 required fields:
  - Bug ID
  - Title
  - Description
  - Priority
  - Status
  - Project Tag
  - Date Logged
  - Last Updated
- Bug ID and Date Logged are auto-generated and not editable by the user.
- Last Updated refreshes automatically whenever a bug is edited.
- Dashboard with 5 live summary counts:
  - Total Bugs
  - Open Bugs
  - In Progress Bugs
  - Resolved Bugs
  - Critical Bugs
- Live search by title and description.
- Combined filters for status, priority, and project tag.
- Project tag filter is populated dynamically from current bug records.
- localStorage persistence after create, edit, and delete actions.
- JSON export as `BugBoxCode_export.json`.
- CSV export as `BugBoxCode_export.csv`.
- 10 pre-loaded sample bug entries on first open when no localStorage data exists.
- Clean pure dark theme UI.
- Responsive layout for desktop, tablet, and smaller screens.

## Data Persistence

Bug data is saved in the browser localStorage under this key:

`BugBoxCode_LoopStack_bugs_v1`

The data is private to the browser and device where the HTML file is opened. To back up or move data, use the JSON or CSV export buttons.

## Export Notes

Both JSON and CSV exports include the full unfiltered dataset, even when search or filters are active in the interface.

## Browser Compatibility

Tested target browsers:

- Current Chrome
- Current Firefox
- Current Microsoft Edge

## Offline Usage

After delivery, the app does not require an internet connection. The logo is integrated into the HTML file, and the app uses no backend, API, npm package, webpack, vite, or build process.
