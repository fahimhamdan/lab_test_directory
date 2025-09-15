# HKL Pathology Test Directory

This is a dynamic web-based directory for pathology tests, connected to Google Sheets.

## Features
- 🔍 Search tests dynamically
- 📑 Filter by:
  - Test Name
  - Performing Lab
  - Specimen Type
- 📄 Pagination (10 / 25 / 50 / All rows per page)
- 📱 Responsive design (works on desktop & mobile)
- 👀 View button to open details in a modal
- 🎨 Modal styled with blue header + white detail area
- ⚡ Data automatically syncs from Google Sheets

## How it works
1. Data is fetched from Google Sheets via JSON endpoint.
2. DataTables.js is used to handle pagination, search, and responsive table.
3. Clicking **View** opens a modal with full test details.

## Setup
1. Host `index.html` locally or on GitHub Pages.
2. Ensure your Google Sheet is published with **Anyone with link can view**.
3. Replace the `sheetId` and `sheetName` in the script if using your own sheet.

## Credits
Designed by Fahim Hamdan
